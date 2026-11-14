<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwh0ln4yx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwh0ln4yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:attachment-off" {...props}></Icon>
