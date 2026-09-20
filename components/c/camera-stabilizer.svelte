<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0dp5vk3o.css';
import '../../css/z/z_z9eib_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w0dp5vk3o"/><path class="z_z9eib_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:camera-stabilizer" {...props}></Icon>
