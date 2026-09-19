<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8ul7ibqd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="p8ul7ibqd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:calendar-bold" {...props}></Icon>
