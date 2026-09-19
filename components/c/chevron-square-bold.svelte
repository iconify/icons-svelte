<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9ys0rl9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="m9ys0rl9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:chevron-square-bold" {...props}></Icon>
