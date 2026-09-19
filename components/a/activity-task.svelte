<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucqddvbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ucqddvbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:activity-task" {...props}></Icon>
