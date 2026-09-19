<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z48inlb-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="z48inlb-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:person-walking-arrow-loop-left" {...props}></Icon>
