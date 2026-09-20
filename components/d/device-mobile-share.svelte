<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r05yhzm4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r05yhzm4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-mobile-share" {...props}></Icon>
