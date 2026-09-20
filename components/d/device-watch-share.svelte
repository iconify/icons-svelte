<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iw-gmiquk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iw-gmiquk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-watch-share" {...props}></Icon>
