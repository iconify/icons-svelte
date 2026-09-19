<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xei7h-0er.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="xei7h-0er"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:relax-bold" {...props}></Icon>
