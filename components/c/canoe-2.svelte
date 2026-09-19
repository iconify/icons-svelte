<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi84yvodx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="xi84yvodx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:canoe-2" {...props}></Icon>
