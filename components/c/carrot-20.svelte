<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkxaczbdn.css';
import '../../css/a/ad8m3acwq.css';
import '../../css/a/apgdcwqaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wkxaczbdn"/><path class="ad8m3acwq"/><path class="apgdcwqaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carrot-20" {...props}></Icon>
