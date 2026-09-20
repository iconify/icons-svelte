<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgte9d-7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgte9d-7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:location-star-outline" {...props}></Icon>
