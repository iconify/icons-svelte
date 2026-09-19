<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3zwszm_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l3zwszm_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:layout-split" {...props}></Icon>
