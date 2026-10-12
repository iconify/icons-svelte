<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iccsyvk3j.css';
import '../../css/y/y9tcibr9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iccsyvk3j"/><path class="y9tcibr9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-video-20-bold" {...props}></Icon>
