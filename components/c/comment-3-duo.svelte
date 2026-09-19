<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9d3mpq3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="w9d3mpq3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:comment-3-duo" {...props}></Icon>
