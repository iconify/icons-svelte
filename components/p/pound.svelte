<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zotwl3b8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zotwl3b8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:pound" {...props}></Icon>
