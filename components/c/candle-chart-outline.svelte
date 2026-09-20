<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9--h4bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="u9--h4bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:candle-chart-outline" {...props}></Icon>
