<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytfd0j2fs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytfd0j2fs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:camera-heart" {...props}></Icon>
