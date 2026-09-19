<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgf0h5e8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":896};
const content = `<path class="vgf0h5e8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:atari" {...props}></Icon>
