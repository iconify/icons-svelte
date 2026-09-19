<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfwi9t47h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfwi9t47h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:groq-ai" {...props}></Icon>
