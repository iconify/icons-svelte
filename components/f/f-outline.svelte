<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4n-xeb2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="l4n-xeb2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:f-outline" {...props}></Icon>
