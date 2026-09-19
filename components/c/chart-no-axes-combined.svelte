<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npsi0gptz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="npsi0gptz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chart-no-axes-combined" {...props}></Icon>
