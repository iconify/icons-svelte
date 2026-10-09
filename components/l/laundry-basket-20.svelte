<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7-lm4bvk.css';
import '../../css/z/zjq3s2ihz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c7-lm4bvk"/><path class="zjq3s2ihz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:laundry-basket-20" {...props}></Icon>
