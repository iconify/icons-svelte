<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/y/ybfqy0wjb.css';
import '../../css/m/mhdr543mh.css';
import '../../css/b/bkja6hbdm.css';
import '../../css/a/abddbewdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco ybfqy0wjb"/><path class="mhdr543mh wm-deco"/><path class="bkja6hbdm"/><path class="abddbewdp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:align-center-blueprint" {...props}></Icon>
