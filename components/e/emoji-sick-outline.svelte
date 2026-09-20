<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4yvs6fct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4yvs6fct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoji-sick-outline" {...props}></Icon>
