<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u9x-w4s1u.css';
import '../../css/o/omx4q5uyw.css';
import '../../css/x/xqh2mbcfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u9x-w4s1u"/><path class="omx4q5uyw"/><path class="xqh2mbcfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-truck-20-bold" {...props}></Icon>
