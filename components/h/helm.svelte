<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptbs4actm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ptbs4actm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:helm" {...props}></Icon>
