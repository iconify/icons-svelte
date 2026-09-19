<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d53h_wb6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="d53h_wb6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:lock-share" {...props}></Icon>
