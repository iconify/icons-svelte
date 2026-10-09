<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yajgwt04s.css';
import '../../css/t/t0m57ubqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yajgwt04s"/><path class="t0m57ubqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-line-20" {...props}></Icon>
