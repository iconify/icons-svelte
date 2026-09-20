<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-g_mmeuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-g_mmeuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-multiple-outline" {...props}></Icon>
