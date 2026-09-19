<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2e-r9t0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e2e-r9t0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:leaderboard-star" {...props}></Icon>
