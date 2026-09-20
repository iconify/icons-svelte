<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6ctxebdq.css';
import '../../css/z/zyi-hacts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j6ctxebdq"/><path class="zyi-hacts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:imdb" {...props}></Icon>
