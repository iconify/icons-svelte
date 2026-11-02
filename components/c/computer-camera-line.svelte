<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldzt82bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldzt82bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:computer-camera-line" {...props}></Icon>
