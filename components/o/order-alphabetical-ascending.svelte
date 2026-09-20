<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsph4ybax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsph4ybax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:order-alphabetical-ascending" {...props}></Icon>
