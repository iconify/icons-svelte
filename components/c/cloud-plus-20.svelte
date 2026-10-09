<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e82l9ab8r.css';
import '../../css/k/k6p64wbai.css';
import '../../css/k/k_yg_y1rk.css';
import '../../css/p/p7-shloum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e82l9ab8r"/><path class="k6p64wbai"/><path class="k_yg_y1rk"/><path class="p7-shloum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-plus-20" {...props}></Icon>
