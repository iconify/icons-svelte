<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffogr3zwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ffogr3zwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:qrcode-scan" {...props}></Icon>
