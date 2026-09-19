<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi65dfb6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="hi65dfb6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:comment-2-duo" {...props}></Icon>
