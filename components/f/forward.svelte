<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvu_vu4pb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":384};
const content = `<path class="tvu_vu4pb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:forward" {...props}></Icon>
