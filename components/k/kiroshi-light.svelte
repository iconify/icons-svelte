<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0umoi1yo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f0umoi1yo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kiroshi-light" {...props}></Icon>
