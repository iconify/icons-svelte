<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rf1lcdbbf.css';
import '../../css/l/li-08qb4y.css';
import '../../css/n/nrth2abtj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rf1lcdbbf"/><path class="li-08qb4y"/><path class="nrth2abtj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:chromecast" {...props}></Icon>
