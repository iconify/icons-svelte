<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/l/lqyf9ccow.css';
import '../../css/z/zw48p_m5a.css';
import '../../css/v/v5jdyxbhx.css';
import '../../css/i/iagn37brf.css';
import '../../css/g/gfnqhtbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="lqyf9ccow wm-deco"/><path class="wm-deco zw48p_m5a"/><path class="v5jdyxbhx wm-deco"/><path class="iagn37brf wm-k"/><path class="gfnqhtbkm wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:library-blueprint" {...props}></Icon>
