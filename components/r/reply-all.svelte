<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/w/wop4crbve.css';
import '../../css/r/r3rj8nbts.css';
import '../../css/r/rt4-vfbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="wm-shadow wop4crbve"/><path class="r3rj8nbts wm-shadow"/><path class="rt4-vfbde"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:reply-all" {...props}></Icon>
