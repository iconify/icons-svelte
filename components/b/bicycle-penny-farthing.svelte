<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7zq3hnll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p7zq3hnll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bicycle-penny-farthing" {...props}></Icon>
