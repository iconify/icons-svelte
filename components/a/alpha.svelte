<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hutwm4b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hutwm4b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:alpha" {...props}></Icon>
