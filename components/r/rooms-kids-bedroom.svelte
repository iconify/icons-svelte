<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vggrv1tof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vggrv1tof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:rooms-kids-bedroom" {...props}></Icon>
