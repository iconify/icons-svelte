<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc9bpyb_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":897};
const content = `<path class="uc9bpyb_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:hexagon" {...props}></Icon>
