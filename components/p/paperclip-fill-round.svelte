<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbc9os0zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wbc9os0zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:paperclip-fill-round" {...props}></Icon>
