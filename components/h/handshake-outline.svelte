<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ojzurcvfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ojzurcvfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:handshake-outline" {...props}></Icon>
