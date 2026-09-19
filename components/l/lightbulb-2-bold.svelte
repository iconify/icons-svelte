<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebp_wrb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="ebp_wrb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:lightbulb-2-bold" {...props}></Icon>
