<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q3bwoucvq.css';
import '../../css/t/tydgjvody.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q3bwoucvq"/><path class="tydgjvody"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:candle-48-bold" {...props}></Icon>
