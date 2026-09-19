<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k16ubbb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="k16ubbb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:paperclip" {...props}></Icon>
