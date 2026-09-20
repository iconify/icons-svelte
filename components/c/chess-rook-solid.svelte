<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i750axr_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i750axr_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:chess-rook-solid" {...props}></Icon>
