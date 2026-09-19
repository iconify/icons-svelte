<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1phebb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="x1phebb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:c-bold" {...props}></Icon>
