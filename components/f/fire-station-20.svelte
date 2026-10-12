<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5bk2nbef.css';
import '../../css/b/bdjsbobgf.css';
import '../../css/w/whrxjkbma.css';
import '../../css/t/tgzsbh4mh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t5bk2nbef"/><path class="bdjsbobgf"/><path class="whrxjkbma"/><path class="tgzsbh4mh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fire-station-20" {...props}></Icon>
