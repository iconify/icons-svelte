<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fixgzfbiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fixgzfbiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:die-4-bold" {...props}></Icon>
