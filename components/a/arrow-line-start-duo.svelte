<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t87l6hbgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="t87l6hbgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-line-start-duo" {...props}></Icon>
