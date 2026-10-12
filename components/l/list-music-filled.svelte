<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9iyuzb1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9iyuzb1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:list-music-filled" {...props}></Icon>
