<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wi8c47b-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wi8c47b-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dashboard-2-fill" {...props}></Icon>
