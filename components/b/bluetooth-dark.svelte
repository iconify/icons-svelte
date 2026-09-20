<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzbpc3vpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tzbpc3vpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:bluetooth-dark" {...props}></Icon>
