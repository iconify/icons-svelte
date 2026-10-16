<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wssriqbjc.css';
import '../../css/y/yvphjmmpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wssriqbjc"/><path class="yvphjmmpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:earthquake-20" {...props}></Icon>
