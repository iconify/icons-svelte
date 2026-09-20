<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvf96rbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvf96rbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hdd" {...props}></Icon>
