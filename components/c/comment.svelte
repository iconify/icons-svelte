<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3c9o6b9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="c3c9o6b9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:comment" {...props}></Icon>
