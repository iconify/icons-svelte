<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybmc9dbzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ybmc9dbzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:multi-select-16" {...props}></Icon>
