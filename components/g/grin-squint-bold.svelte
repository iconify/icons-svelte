<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8ws7ybzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="r8ws7ybzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grin-squint-bold" {...props}></Icon>
