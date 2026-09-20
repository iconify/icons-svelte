<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhhatui_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhhatui_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:menu" {...props}></Icon>
