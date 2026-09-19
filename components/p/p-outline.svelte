<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt89g0bgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="nt89g0bgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:p-outline" {...props}></Icon>
