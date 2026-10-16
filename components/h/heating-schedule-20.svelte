<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjzgm6b2a.css';
import '../../css/k/ktpspx8sw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yjzgm6b2a"/><path class="ktpspx8sw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heating-schedule-20" {...props}></Icon>
