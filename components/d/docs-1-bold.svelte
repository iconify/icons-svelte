<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2f5-g1mk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="z2f5-g1mk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:docs-1-bold" {...props}></Icon>
