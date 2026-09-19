<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyajd4b5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="gyajd4b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hash" {...props}></Icon>
