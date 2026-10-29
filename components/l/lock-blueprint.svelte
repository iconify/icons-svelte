<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/p/p5a8rkbkg.css';
import '../../css/q/qaz708b7b.css';
import '../../css/a/ayhs6pbko.css';
import '../../css/n/nvjwwccph.css';
import '../../css/n/nz1qr5btk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="p5a8rkbkg wm-deco"/><path class="qaz708b7b wm-deco"/><path class="ayhs6pbko wm-deco"/><path class="nvjwwccph wm-k"/><path class="nz1qr5btk wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:lock-blueprint" {...props}></Icon>
