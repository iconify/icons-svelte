<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtknkcbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="rtknkcbgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:circle-half-2-outline" {...props}></Icon>
