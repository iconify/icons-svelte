<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s82-gfb1o.css';
import '../../css/v/vs4bry39s.css';
import '../../css/f/fj5kn0w7n.css';
import '../../css/u/uedre7bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s82-gfb1o"/><path class="vs4bry39s"/><path class="fj5kn0w7n"/><path class="uedre7bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mosque-48" {...props}></Icon>
