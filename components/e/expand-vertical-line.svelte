<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j06br4mtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j06br4mtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-vertical-line" {...props}></Icon>
