<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdiltt19v.css';
import '../../css/r/rvji97b-y.css';
import '../../css/h/hsuwmebtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xdiltt19v"/><path class="rvji97b-y"/><path class="hsuwmebtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:analytics-20-bold" {...props}></Icon>
