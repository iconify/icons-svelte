<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6s-tdxlh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="n6s-tdxlh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:o-outline" {...props}></Icon>
