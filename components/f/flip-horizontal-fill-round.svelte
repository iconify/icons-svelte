<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkdfjcb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkdfjcb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:flip-horizontal-fill-round" {...props}></Icon>
