<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8i3b9xno.css';
import '../../css/x/xbxy7ib5r.css';
import '../../css/c/c0tgf1saz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x8i3b9xno"/><path class="xbxy7ib5r"/><path class="c0tgf1saz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-note-2-bold-duotone" {...props}></Icon>
