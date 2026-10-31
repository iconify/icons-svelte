<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/f/frqvhkbha.css';
import '../../css/h/h1r7qx2rk.css';
import '../../css/h/h48vv8brj.css';
import '../../css/w/w27peibbj.css';
import '../../css/v/vtv5mlorn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="frqvhkbha"/><path class="h1r7qx2rk wm-shine"/><path class="h48vv8brj wm-k"/><path class="w27peibbj wm-a"/><path class="vtv5mlorn wm-deco"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:black-cat" {...props}></Icon>
