<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdbfdz6em.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="pdbfdz6em"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-2-bold" {...props}></Icon>
