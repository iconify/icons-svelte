<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddfy9kbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddfy9kbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:golf-gloss" {...props}></Icon>
