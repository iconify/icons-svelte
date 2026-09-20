<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j72t7j6ih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j72t7j6ih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:chart-bar-increasing-solid" {...props}></Icon>
