<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g0ni6vb5b.css';
import '../../css/w/wl476na-m.css';
import '../../css/r/riruf7bad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g0ni6vb5b"/><path class="wl476na-m"/><path class="riruf7bad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:canal-lock-20" {...props}></Icon>
