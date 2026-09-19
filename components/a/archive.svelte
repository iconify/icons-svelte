<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu1nvub7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="lu1nvub7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:archive" {...props}></Icon>
