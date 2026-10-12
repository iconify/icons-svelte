<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/its8f7byw.css';
import '../../css/j/j4t0g_avv.css';
import '../../css/i/im-u2lvxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="its8f7byw"/><path class="j4t0g_avv"/><path class="im-u2lvxf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:globe-check-duotone" {...props}></Icon>
