<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xvzp7mbxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="xvzp7mbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pennant-1" {...props}></Icon>
