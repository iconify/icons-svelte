<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zll1bu97z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zll1bu97z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:camera-ai-2-line" {...props}></Icon>
