<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwur2ebbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwur2ebbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rewind-backward-5-line" {...props}></Icon>
