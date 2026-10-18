<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r24r7qt7r.css';
import '../../css/x/xuu2b7bwb.css';
import '../../css/c/ct_c29f3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="r24r7qt7r"/><path class="xuu2b7bwb"/><path class="ct_c29f3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:drone-inspection-20" {...props}></Icon>
