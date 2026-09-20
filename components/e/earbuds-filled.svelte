<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/sw1u15auk.css';
import '../../css/y/yci9rb1mt.css';
import '../../css/n/n5-k2h8fg.css';
import '../../css/p/pzr5cxfbm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="sw1u15auk"/><path class="yci9rb1mt"/><path clip-rule="evenodd" class="n5-k2h8fg"/><path class="pzr5cxfbm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:earbuds-filled" {...props}></Icon>
