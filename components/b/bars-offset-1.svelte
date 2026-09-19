<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp2s7bc1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="bp2s7bc1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bars-offset-1" {...props}></Icon>
