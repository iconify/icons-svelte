<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c846f2b3u.css';
import '../../css/c/c2gy29bva.css';
import '../../css/w/wj_gkq1ud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="c846f2b3u"/><path class="c2gy29bva"/><path class="wj_gkq1ud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:kubernetes-wordmark" {...props}></Icon>
