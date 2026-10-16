<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7yzfib3b.css';
import '../../css/v/vwz64_bea.css';
import '../../css/s/srjhv05-x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v7yzfib3b"/><path class="vwz64_bea"/><path class="srjhv05-x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:air-fryer-20" {...props}></Icon>
