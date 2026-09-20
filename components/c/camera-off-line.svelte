<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qlls62c1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qlls62c1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:camera-off-line" {...props}></Icon>
