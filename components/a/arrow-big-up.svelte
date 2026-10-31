<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dkv48acbf.css';
import '../../css/y/y5bh3jb9c.css';
import '../../css/p/p83undbxt.css';
import '../../css/m/m-32ofbyd.css';
import '../../css/y/yuobg4bux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="y5bh3jb9c"/><path class="p83undbxt wm-shine"/><path class="m-32ofbyd"/><path class="wm-deco yuobg4bux"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-kawaii:arrow-big-up" {...props}></Icon>
