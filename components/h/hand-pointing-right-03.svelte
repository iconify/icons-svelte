<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wg9unib3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wg9unib3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:hand-pointing-right-03" {...props}></Icon>
