<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u48joobhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u48joobhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:loop-right-ai-line" {...props}></Icon>
