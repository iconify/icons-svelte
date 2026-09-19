<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/non__abbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="non__abbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:celsius" {...props}></Icon>
