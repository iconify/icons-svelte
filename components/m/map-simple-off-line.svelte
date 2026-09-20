<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d6r0bob8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6r0bob8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:map-simple-off-line" {...props}></Icon>
