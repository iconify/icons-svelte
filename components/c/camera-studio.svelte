<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkm14zb_u.css';
import '../../css/e/emrf_55ka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkm14zb_u"/><path class="emrf_55ka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:camera-studio" {...props}></Icon>
