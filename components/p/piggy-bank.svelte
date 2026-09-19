<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1x5o90gz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<path class="q1x5o90gz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:piggy-bank" {...props}></Icon>
