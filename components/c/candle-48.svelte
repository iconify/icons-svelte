<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvshp_bta.css';
import '../../css/a/a1o2reb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jvshp_bta"/><path class="a1o2reb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:candle-48" {...props}></Icon>
