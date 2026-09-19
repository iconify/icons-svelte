<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd9umdbmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd9umdbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:alarm-off" {...props}></Icon>
