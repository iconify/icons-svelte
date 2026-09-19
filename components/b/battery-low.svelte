<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpc92sept.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpc92sept"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:battery-low" {...props}></Icon>
