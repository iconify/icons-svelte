<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cppjm0jfh.css';
import '../../css/m/mz0wy9bse.css';
import '../../css/w/wangxwr8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="cppjm0jfh"/><path class="mz0wy9bse"/><path class="wangxwr8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pipe-wrench-48" {...props}></Icon>
