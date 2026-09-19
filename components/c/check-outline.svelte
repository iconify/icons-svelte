<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stpoqex2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="stpoqex2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:check-outline" {...props}></Icon>
