<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwor0sbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nwor0sbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heart-half-1-outline" {...props}></Icon>
