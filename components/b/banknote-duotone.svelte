<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rk_xybcdo.css';
import '../../css/r/rnmmgzb7q.css';
import '../../css/d/dbth34zxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rk_xybcdo"/><path class="rnmmgzb7q"/><path clip-rule="evenodd" class="dbth34zxp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:banknote-duotone" {...props}></Icon>
