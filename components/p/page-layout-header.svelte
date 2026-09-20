<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zu4q4-rfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zu4q4-rfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:page-layout-header" {...props}></Icon>
