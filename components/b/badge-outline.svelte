<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbuc5572w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="mbuc5572w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:badge-outline" {...props}></Icon>
