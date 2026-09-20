<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j60fy-bcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j60fy-bcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:local-movies" {...props}></Icon>
