<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c984stk_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="c984stk_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pause" {...props}></Icon>
