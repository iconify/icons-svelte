<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc9v-pb0v.css';
import '../../css/i/i79qx-ncx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc9v-pb0v"/><path class="i79qx-ncx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:hard-drive-exertnal-1" {...props}></Icon>
