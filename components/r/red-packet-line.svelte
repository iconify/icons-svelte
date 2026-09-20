<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmup1_bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xmup1_bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:red-packet-line" {...props}></Icon>
