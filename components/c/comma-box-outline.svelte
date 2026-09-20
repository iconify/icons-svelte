<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2m4sxbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2m4sxbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comma-box-outline" {...props}></Icon>
