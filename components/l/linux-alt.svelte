<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xstgp02xk.css';
import '../../css/t/tn_hnfb5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xstgp02xk"/><path class="tn_hnfb5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:linux-alt" {...props}></Icon>
