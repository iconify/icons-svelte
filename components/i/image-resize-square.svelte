<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yf4rofglg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yf4rofglg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:image-resize-square" {...props}></Icon>
