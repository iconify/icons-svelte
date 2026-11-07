<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxy3rfbfq.css';
import '../../css/k/kngzmjb8s.css';
import '../../css/e/eyyfu1tja.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxy3rfbfq"/><path class="kngzmjb8s"/><path class="eyyfu1tja"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:box-minimalistic-bold-duotone" {...props}></Icon>
