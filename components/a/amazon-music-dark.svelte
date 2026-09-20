<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-5jfr_yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y-5jfr_yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-music-dark" {...props}></Icon>
