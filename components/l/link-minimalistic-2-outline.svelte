<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbykibczi.css';
import '../../css/f/fm67_nbcb.css';
import '../../css/r/r7elkeb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbykibczi"/><path class="fm67_nbcb"/><path class="r7elkeb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:link-minimalistic-2-outline" {...props}></Icon>
