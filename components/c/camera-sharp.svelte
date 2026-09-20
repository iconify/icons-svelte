<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ppplzd1pw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ppplzd1pw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:camera-sharp" {...props}></Icon>
