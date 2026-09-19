<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhitcdc0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="fhitcdc0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heartbreak-bold" {...props}></Icon>
