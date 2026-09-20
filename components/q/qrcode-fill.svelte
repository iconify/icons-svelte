<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mym01l9ah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mym01l9ah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:qrcode-fill" {...props}></Icon>
