<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6h5rcbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6h5rcbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:music-note" {...props}></Icon>
