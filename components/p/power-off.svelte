<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4sf1r5oy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4sf1r5oy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:power-off" {...props}></Icon>
