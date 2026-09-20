<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5ydwh_7g.css';
import '../../css/m/mgkytmtsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u5ydwh_7g"/><path class="mgkytmtsq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:anchor-top-middle-16" {...props}></Icon>
