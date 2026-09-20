<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yef25-vzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yef25-vzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pentagon-fill" {...props}></Icon>
