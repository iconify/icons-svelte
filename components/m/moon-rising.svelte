<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thid7e.css';
import '../../css/c/c_rqdr.css';
import '../../css/y/ydovum.css';
import '../../css/x/xhxeiv.css';
import '../../css/d/d-k-hl-x.css';
import '../../css/f/fade-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="thid7e"/><path class="c_rqdr ydovum"/><path class="xhxeiv ydovum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:moon-rising" {...props}></Icon>
