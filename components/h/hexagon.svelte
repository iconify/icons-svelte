<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uugfhkbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uugfhkbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:hexagon" {...props}></Icon>
