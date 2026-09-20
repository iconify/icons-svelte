<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcho64smd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xcho64smd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:haze-solid" {...props}></Icon>
