<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/utf77lbef.css';
import '../../css/n/nb144-0ui.css';
import '../../css/d/dku8h8g5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="utf77lbef"/><path class="nb144-0ui"/><path class="dku8h8g5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:merit-order-48" {...props}></Icon>
