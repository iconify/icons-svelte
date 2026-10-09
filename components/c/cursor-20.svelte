<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yio_babqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yio_babqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cursor-20" {...props}></Icon>
