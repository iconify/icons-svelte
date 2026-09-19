<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0ryvgb7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="i0ryvgb7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-peace-duo" {...props}></Icon>
