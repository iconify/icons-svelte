<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v05au6sye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v05au6sye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:anticlockwise-fill" {...props}></Icon>
