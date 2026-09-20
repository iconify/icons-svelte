<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/umbcrlb4m.css';
import '../../css/k/kmzsj98hw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="umbcrlb4m"/><path class="kmzsj98hw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pie-chart-solid" {...props}></Icon>
