<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd84xvgpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd84xvgpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:looks-3" {...props}></Icon>
