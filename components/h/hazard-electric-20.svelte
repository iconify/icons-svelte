<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6_s1zkbf.css';
import '../../css/t/t64wjlb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e6_s1zkbf"/><path class="t64wjlb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hazard-electric-20" {...props}></Icon>
