<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqmaimblk.css';
import '../../css/j/j7wys6bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lqmaimblk"/><path class="j7wys6bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-rocket" {...props}></Icon>
