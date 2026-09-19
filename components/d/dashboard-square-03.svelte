<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnbmphelx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnbmphelx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dashboard-square-03" {...props}></Icon>
