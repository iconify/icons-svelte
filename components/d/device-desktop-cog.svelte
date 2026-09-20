<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck5ihzb4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ck5ihzb4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-desktop-cog" {...props}></Icon>
