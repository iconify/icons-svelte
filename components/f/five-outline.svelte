<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7707_6ks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="x7707_6ks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:five-outline" {...props}></Icon>
