<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3g1x1bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="b3g1x1bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-outline" {...props}></Icon>
