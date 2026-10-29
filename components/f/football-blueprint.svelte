<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9nmekbvz.css';
import '../../css/y/yzln40bxl.css';
import '../../css/y/ynh3ncb9f.css';
import '../../css/u/ut75iob1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="wm-deco yzln40bxl"/><path class="wm-deco ynh3ncb9f"/><path class="ut75iob1g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:football-blueprint" {...props}></Icon>
