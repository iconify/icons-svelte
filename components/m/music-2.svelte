<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8t-i12hw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8t-i12hw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:music-2" {...props}></Icon>
