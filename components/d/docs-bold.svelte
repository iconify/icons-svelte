<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f7c4ygb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="f7c4ygb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:docs-bold" {...props}></Icon>
