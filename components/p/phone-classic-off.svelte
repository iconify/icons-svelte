<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1gp6sb5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x1gp6sb5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-classic-off" {...props}></Icon>
