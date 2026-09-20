<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/se3cadkfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="se3cadkfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:corner-down-right-fill" {...props}></Icon>
