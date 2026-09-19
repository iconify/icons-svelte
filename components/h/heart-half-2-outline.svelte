<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7ko7b07r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="p7ko7b07r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heart-half-2-outline" {...props}></Icon>
