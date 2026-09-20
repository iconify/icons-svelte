<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ys-mqb6ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ys-mqb6ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:call-bell-outline" {...props}></Icon>
