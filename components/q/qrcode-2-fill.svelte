<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vy2sqfbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vy2sqfbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:qrcode-2-fill" {...props}></Icon>
