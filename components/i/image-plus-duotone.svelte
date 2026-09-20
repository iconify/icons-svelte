<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2g_mm_im.css';
import '../../css/i/iz8c3l5-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2g_mm_im"/><path class="iz8c3l5-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:image-plus-duotone" {...props}></Icon>
