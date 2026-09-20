<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewru3_btl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewru3_btl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:gesture-typing-filled" {...props}></Icon>
