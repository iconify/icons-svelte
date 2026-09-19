<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhnlb3m2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="vhnlb3m2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:modulo" {...props}></Icon>
