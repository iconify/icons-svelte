<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szs2yjbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="szs2yjbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:comment-duo" {...props}></Icon>
