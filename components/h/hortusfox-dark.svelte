<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5u0_elga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f5u0_elga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hortusfox-dark" {...props}></Icon>
