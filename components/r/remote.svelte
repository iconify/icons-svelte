<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj8g_sb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uj8g_sb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:remote" {...props}></Icon>
