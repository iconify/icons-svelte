<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5fytvx5z.css';
import '../../css/s/s8208dgjy.css';
import '../../css/l/lxculd_tv.css';
import '../../css/x/xh5w7ub4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d5fytvx5z"/><path class="s8208dgjy"/><path class="lxculd_tv"/><path class="xh5w7ub4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:abacus-20-bold" {...props}></Icon>
