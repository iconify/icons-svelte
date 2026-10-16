<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6t6ne13x.css';
import '../../css/v/vjvtfabym.css';
import '../../css/v/vpb3bu46w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j6t6ne13x"/><path class="vjvtfabym"/><path class="vpb3bu46w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ammonia-tank-48-bold" {...props}></Icon>
