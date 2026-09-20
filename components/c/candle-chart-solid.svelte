<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j0wtvdbfd.css';
import '../../css/r/rn0avuaev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j0wtvdbfd"/><path class="rn0avuaev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:candle-chart-solid" {...props}></Icon>
