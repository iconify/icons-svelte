<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzfv1-bcy.css';
import '../../css/w/wqemgtbkk.css';
import '../../css/x/x36h73bpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qzfv1-bcy"/><path class="wqemgtbkk"/><path class="x36h73bpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-valve-20-bold" {...props}></Icon>
