<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zro89qjwt.css';
import '../../css/v/vwrn1bbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zro89qjwt"/><path class="vwrn1bbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-solar-48-bold" {...props}></Icon>
