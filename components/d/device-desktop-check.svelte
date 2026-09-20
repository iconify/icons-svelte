<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-ja3_bwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-ja3_bwq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-desktop-check" {...props}></Icon>
