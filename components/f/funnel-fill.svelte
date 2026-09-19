<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkzgt2baw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vkzgt2baw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:funnel-fill" {...props}></Icon>
