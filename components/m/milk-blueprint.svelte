<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/g/gz61a7bkh.css';
import '../../css/r/rbzq4bjzv.css';
import '../../css/e/e8y0qijnn.css';
import '../../css/q/qmf8_bm9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="gz61a7bkh wm-deco"/><path class="rbzq4bjzv wm-deco"/><path class="e8y0qijnn wm-k"/><path class="qmf8_bm9e wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:milk-blueprint" {...props}></Icon>
