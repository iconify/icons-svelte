<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oogt8rbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oogt8rbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-music-outline" {...props}></Icon>
