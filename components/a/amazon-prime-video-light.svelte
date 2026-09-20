<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5s8bqb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g5s8bqb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-prime-video-light" {...props}></Icon>
