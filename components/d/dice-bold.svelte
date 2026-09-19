<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-9eorpun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="y-9eorpun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:dice-bold" {...props}></Icon>
