<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s53e0bcnh.css';
import '../../css/p/phkuhv_dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s53e0bcnh"/><path class="phkuhv_dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:connectwise-brightgauge-light" {...props}></Icon>
