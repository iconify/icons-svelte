<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvaqon8oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvaqon8oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hearts-fill" {...props}></Icon>
