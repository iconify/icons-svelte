<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwa99fblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="uwa99fblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:one-bold" {...props}></Icon>
