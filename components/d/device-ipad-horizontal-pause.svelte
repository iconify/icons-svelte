<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdrfb-tbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdrfb-tbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-ipad-horizontal-pause" {...props}></Icon>
