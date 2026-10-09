<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scv2f5bpz.css';
import '../../css/x/xk2zqv2dn.css';
import '../../css/g/g33vo8vvy.css';
import '../../css/u/um41547jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="scv2f5bpz"/><path class="xk2zqv2dn"/><path class="g33vo8vvy"/><path class="um41547jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:construction-crane-20-bold" {...props}></Icon>
