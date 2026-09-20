<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwiaqi-vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwiaqi-vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:module-puzzle-2" {...props}></Icon>
