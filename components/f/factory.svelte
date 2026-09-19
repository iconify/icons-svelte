<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-h9r1mla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p-h9r1mla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:factory" {...props}></Icon>
