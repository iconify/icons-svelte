<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8bxqwb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="z8bxqwb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:b-duo" {...props}></Icon>
