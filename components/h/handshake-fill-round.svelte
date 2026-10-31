<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t06y_mbts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t06y_mbts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:handshake-fill-round" {...props}></Icon>
