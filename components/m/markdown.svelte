<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnin-bbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pnin-bbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:markdown" {...props}></Icon>
