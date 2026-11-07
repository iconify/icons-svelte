<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1ktr8brq.css';
import '../../css/m/mug5xin-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1ktr8brq"/><path class="mug5xin-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pulse-2-bold-duotone" {...props}></Icon>
