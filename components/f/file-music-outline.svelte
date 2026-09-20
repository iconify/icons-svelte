<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq5o1ytlu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq5o1ytlu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-music-outline" {...props}></Icon>
