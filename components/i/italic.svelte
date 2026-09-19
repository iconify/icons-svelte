<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqm8r7dhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="oqm8r7dhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:italic" {...props}></Icon>
