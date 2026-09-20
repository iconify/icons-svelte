<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf06j_bww.css';
import '../../css/r/rsco9dbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bf06j_bww"/><path class="rsco9dbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-skull-2" {...props}></Icon>
