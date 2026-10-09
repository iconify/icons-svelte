<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xhpycbbzt.css';
import '../../css/g/gxdkw6pqr.css';
import '../../css/k/kp3z9vp1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xhpycbbzt"/><path class="gxdkw6pqr"/><path class="kp3z9vp1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gift-48" {...props}></Icon>
