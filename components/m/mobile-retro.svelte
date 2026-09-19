<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyl-3tbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="vyl-3tbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:mobile-retro" {...props}></Icon>
