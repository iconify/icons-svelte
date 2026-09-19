<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1zkx-b_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1zkx-b_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:border-vertical" {...props}></Icon>
