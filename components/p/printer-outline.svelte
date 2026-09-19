<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb5vv-0rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="pb5vv-0rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:printer-outline" {...props}></Icon>
