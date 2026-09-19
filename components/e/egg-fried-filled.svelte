<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scu8uw9wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scu8uw9wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:egg-fried-filled" {...props}></Icon>
