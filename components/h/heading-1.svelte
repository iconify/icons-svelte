<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vk7-uhbzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vk7-uhbzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:heading-1" {...props}></Icon>
