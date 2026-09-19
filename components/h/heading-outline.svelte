<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9wylob2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="a9wylob2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heading-outline" {...props}></Icon>
