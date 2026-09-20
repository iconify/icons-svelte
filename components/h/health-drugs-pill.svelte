<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tet16qbak.css';
import '../../css/w/w_q_buz-q.css';
import '../../css/z/zar5c9-1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tet16qbak"/><path class="w_q_buz-q"/><path class="zar5c9-1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-drugs-pill" {...props}></Icon>
