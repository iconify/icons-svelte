<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5e0hoqob.css';
import '../../css/x/x1tzk_mhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e5e0hoqob"/><path class="x1tzk_mhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bathtub-20-bold" {...props}></Icon>
