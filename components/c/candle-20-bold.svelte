<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uoazbdbsd.css';
import '../../css/r/rzmdligbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="uoazbdbsd"/><path class="rzmdligbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:candle-20-bold" {...props}></Icon>
