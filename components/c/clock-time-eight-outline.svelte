<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lzg8wbc9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lzg8wbc9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clock-time-eight-outline" {...props}></Icon>
