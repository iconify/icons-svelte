<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvafd1y8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvafd1y8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pyramid-filled" {...props}></Icon>
