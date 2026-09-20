<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq50gkoiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq50gkoiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:projector-off" {...props}></Icon>
