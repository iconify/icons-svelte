<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1rfrbc2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<rect class="y1rfrbc2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:player-stop" {...props}></Icon>
