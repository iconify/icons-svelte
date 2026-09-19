<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cy8o92x7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="cy8o92x7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pen-fountain-outline" {...props}></Icon>
