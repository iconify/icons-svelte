<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iggmv2kty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iggmv2kty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-ai-line" {...props}></Icon>
