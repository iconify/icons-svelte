<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru0y2vl2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru0y2vl2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:iframe-brackets-outline" {...props}></Icon>
