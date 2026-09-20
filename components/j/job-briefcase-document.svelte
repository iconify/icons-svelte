<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/l/lezyyqbrb.css';
import '../../css/y/yfyu5b4ac.css';
import '../../css/r/rhuwopb-f.css';
import '../../css/s/sw0djkbmk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="lezyyqbrb"/><path class="yfyu5b4ac"/><path class="rhuwopb-f"/><path class="sw0djkbmk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:job-briefcase-document" {...props}></Icon>
