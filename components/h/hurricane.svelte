<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw45ad8_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="xw45ad8_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:hurricane" {...props}></Icon>
