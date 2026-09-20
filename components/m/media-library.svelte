<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rreixub1u.css';
import '../../css/e/ezppmdskh.css';
import '../../css/y/yhr7tbcrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rreixub1u"/><path class="ezppmdskh"/><path class="yhr7tbcrq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:media-library" {...props}></Icon>
