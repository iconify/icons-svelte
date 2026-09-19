<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5uo-2b8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="l5uo-2b8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:intersect-outline" {...props}></Icon>
