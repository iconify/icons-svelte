<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ttl5mlb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ttl5mlb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:diamond" {...props}></Icon>
