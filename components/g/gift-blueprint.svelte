<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/u/ufn3m0bhg.css';
import '../../css/h/hfgvspbxq.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/b/bz_co8e9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ufn3m0bhg wm-deco"/><path class="hfgvspbxq wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="bz_co8e9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:gift-blueprint" {...props}></Icon>
