<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saj1t_9ca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="saj1t_9ca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:columns" {...props}></Icon>
