<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/dsmleib8v.css';
import '../../css/k/k7fwg9blz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dsmleib8v"/><path clip-rule="evenodd" class="k7fwg9blz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:inpicture" {...props}></Icon>
