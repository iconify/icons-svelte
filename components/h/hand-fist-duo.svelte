<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5f1l6b2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="i5f1l6b2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hand-fist-duo" {...props}></Icon>
