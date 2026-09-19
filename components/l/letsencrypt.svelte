<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkjp8n2ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkjp8n2ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:letsencrypt" {...props}></Icon>
