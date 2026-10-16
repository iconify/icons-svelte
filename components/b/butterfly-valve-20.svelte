<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5dxwccjh.css';
import '../../css/k/kej-obbqo.css';
import '../../css/n/n-e5m9_wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e5dxwccjh"/><path class="kej-obbqo"/><path class="n-e5m9_wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:butterfly-valve-20" {...props}></Icon>
