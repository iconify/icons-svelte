<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/l/l4zmzkh2z.css';
import '../../css/r/rfii-0k4v.css';
import '../../css/g/gdh659iej.css';
import '../../css/p/pz7_a8apx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="l4zmzkh2z wm-deco"/><circle class="rfii-0k4v wm-k"/><circle class="gdh659iej wm-a"/><path class="pz7_a8apx wm-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:award-blueprint" {...props}></Icon>
