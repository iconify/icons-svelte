<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm0dtlbqb.css';
import '../../css/k/ko9a2zbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hm0dtlbqb"/><path class="ko9a2zbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-truck-20" {...props}></Icon>
