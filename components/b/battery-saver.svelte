<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxy9imbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wxy9imbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-saver" {...props}></Icon>
