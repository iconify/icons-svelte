<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/p/p9qcgac9q.css';
import '../../css/u/uuupksbft.css';
import '../../css/o/o7-ag87sb.css';
import '../../css/i/i6x7mbc2d.css';
import '../../css/a/agyau5bzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="p9qcgac9q wm-deco"/><path class="uuupksbft wm-deco"/><path class="o7-ag87sb wm-deco"/><path class="i6x7mbc2d"/><path class="agyau5bzf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:crop-blueprint" {...props}></Icon>
