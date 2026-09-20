<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp2l--bwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rp2l--bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:distribute-horizontal-left" {...props}></Icon>
