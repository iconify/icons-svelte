<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx5qtx73f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rx5qtx73f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:rotate-clockwise" {...props}></Icon>
