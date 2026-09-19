<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuqwgmbol.css';
import '../../css/s/sg2hhebqo.css';
import '../../css/a/ahkvt_bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wuqwgmbol"/><path class="sg2hhebqo"/><path class="ahkvt_bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:doughnut-chart" {...props}></Icon>
