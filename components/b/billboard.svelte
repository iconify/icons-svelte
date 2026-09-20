<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8jcy-bfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8jcy-bfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:billboard" {...props}></Icon>
