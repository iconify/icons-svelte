<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cu7qyy4za.css';
import '../../css/l/lx_8qqvkc.css';
import '../../css/d/d0b6c1bum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="cu7qyy4za"/><path class="lx_8qqvkc"/><path class="d0b6c1bum"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:phone-remove-bold" {...props}></Icon>
