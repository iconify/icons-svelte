<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6h0z-b7o.css';
import '../../css/v/vkg5fb8sm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i6h0z-b7o"/><path class="vkg5fb8sm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:case-round-minimalistic-bold-duotone" {...props}></Icon>
