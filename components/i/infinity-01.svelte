<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rno8pab4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rno8pab4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:infinity-01" {...props}></Icon>
