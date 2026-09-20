<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szb74yk6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="szb74yk6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bookmark-off" {...props}></Icon>
