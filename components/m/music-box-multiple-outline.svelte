<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iduxaeb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iduxaeb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:music-box-multiple-outline" {...props}></Icon>
