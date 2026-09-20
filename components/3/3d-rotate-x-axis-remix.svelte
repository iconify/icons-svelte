<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2wy2ubck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l2wy2ubck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:3d-rotate-x-axis-remix" {...props}></Icon>
