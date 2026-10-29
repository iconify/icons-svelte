<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/b/bemidachf.css';
import '../../css/g/g2xclxbug.css';
import '../../css/b/bt34uhgkb.css';
import '../../css/g/gzqs1_b0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="bemidachf wm-deco"/><path class="g2xclxbug wm-deco"/><path class="bt34uhgkb"/><path class="gzqs1_b0g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:audio-waveform-blueprint" {...props}></Icon>
