<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iiaha8smm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iiaha8smm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dns-outline" {...props}></Icon>
