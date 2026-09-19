<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpocgmcex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cpocgmcex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bounding-box" {...props}></Icon>
