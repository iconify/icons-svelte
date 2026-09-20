<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd8fy92kx.css';
import '../../css/j/jx5rxd8gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd8fy92kx"/><path class="jx5rxd8gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:monitor-sync-bold" {...props}></Icon>
