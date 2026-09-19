<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufy_ol7bn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ufy_ol7bn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:drop-water" {...props}></Icon>
