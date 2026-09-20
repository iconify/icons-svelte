<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qj-hv3b_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qj-hv3b_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adminerevo" {...props}></Icon>
