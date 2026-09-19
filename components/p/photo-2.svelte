<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rr5w0b1hl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="rr5w0b1hl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:photo-2" {...props}></Icon>
