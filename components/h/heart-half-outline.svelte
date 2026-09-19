<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omrej3mio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="omrej3mio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heart-half-outline" {...props}></Icon>
