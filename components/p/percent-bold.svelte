<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1bmkqy-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="j1bmkqy-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:percent-bold" {...props}></Icon>
