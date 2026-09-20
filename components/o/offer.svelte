<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw9lk9bet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uw9lk9bet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:offer" {...props}></Icon>
