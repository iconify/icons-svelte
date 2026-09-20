<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb-9lm2dm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb-9lm2dm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:robot-face-sad-sharp" {...props}></Icon>
