<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zahkbf3tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="zahkbf3tz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:align-side-duo" {...props}></Icon>
