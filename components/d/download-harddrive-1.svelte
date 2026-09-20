<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/a/a8xel1b0w.css';
import '../../css/x/xyxipfb_h.css';
import '../../css/b/btvmlsfwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="a8xel1b0w"/><path class="xyxipfb_h"/><path class="btvmlsfwv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:download-harddrive-1" {...props}></Icon>
