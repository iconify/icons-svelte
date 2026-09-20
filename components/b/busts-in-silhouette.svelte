<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvantbcbw.css';
import '../../css/k/kdz4acc8r.css';
import '../../css/e/ec3ftbzyw.css';
import '../../css/t/tj2_w8ydf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="fvantbcbw"/><g class="kdz4acc8r"><path class="ec3ftbzyw"/><path class="tj2_w8ydf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:busts-in-silhouette" {...props}></Icon>
