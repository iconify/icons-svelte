<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/n/n2e9gzhha.css';
import '../../css/w/wbmwqdh8m.css';
import '../../css/p/p9icysbnd.css';
import '../../css/u/uoi7kccyu.css';
import '../../css/w/w-8p90bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="n2e9gzhha wm-deco"/><path class="wbmwqdh8m wm-deco"/><path class="p9icysbnd wm-deco"/><path class="uoi7kccyu"/><path class="w-8p90bcf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:playground-blueprint" {...props}></Icon>
