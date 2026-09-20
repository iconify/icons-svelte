<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/aw-y6obss.css';
import '../../css/i/irnyb8bbi.css';
import '../../css/w/wuvczemwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="aw-y6obss"/><path class="irnyb8bbi"/><path clip-rule="evenodd" class="wuvczemwq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:info-circle-outline" {...props}></Icon>
