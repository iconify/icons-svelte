<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyf_n7bla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="zyf_n7bla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:plane-side" {...props}></Icon>
