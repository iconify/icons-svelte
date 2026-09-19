<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9q9quzbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="d9q9quzbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-level" {...props}></Icon>
