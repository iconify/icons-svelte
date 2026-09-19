<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j284f22vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j284f22vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:first-brecket" {...props}></Icon>
