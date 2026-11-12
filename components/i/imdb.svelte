<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6ctxebdq.css';
import '../../css/z/zy9gfcbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j6ctxebdq"/><path class="zy9gfcbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:imdb" {...props}></Icon>
