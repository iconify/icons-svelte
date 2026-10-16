<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypa03g2ao.css';
import '../../css/c/c0-sywbwt.css';
import '../../css/v/v45g71edj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ypa03g2ao"/><path class="c0-sywbwt"/><path class="v45g71edj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:currency-exchange-48" {...props}></Icon>
