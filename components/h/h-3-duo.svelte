<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aoeo9--2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="aoeo9--2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:h-3-duo" {...props}></Icon>
