<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6b4ggwjw.css';
import '../../css/w/wh3bwybmx.css';
import '../../css/q/qimpewblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u6b4ggwjw"/><path class="wh3bwybmx"/><path class="qimpewblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:ecology-renewable-energy-wind-turbine" {...props}></Icon>
