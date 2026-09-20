<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjzuz0oew.css';
import '../../css/d/dfd8n3ylg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjzuz0oew"/><path clip-rule="evenodd" class="dfd8n3ylg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bell-bing-outline" {...props}></Icon>
