<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr7xbdwkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sr7xbdwkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:phone-off" {...props}></Icon>
