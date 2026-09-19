<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc0sti72g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yc0sti72g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bitcoin" {...props}></Icon>
