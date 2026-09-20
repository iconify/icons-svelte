<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i0mshkbiy.css';
import '../../css/h/hbya5l-0v.css';
import '../../css/d/d7557zb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i0mshkbiy"/><path clip-rule="evenodd" class="hbya5l-0v"/><path class="d7557zb1x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:money-plus2" {...props}></Icon>
