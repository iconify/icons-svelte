<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv-c2w6li.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="jv-c2w6li"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-bold" {...props}></Icon>
