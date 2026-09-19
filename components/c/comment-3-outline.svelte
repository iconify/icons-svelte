<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q7vnnsbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="q7vnnsbng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:comment-3-outline" {...props}></Icon>
