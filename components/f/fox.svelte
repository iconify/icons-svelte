<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnlz8vwcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="dnlz8vwcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:fox" {...props}></Icon>
