<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ijm19vbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ijm19vbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:paperclip-outline" {...props}></Icon>
