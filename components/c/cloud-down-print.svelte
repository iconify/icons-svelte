<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bbxdvzjvn.css';
import '../../css/y/ypdia9bkn.css';
import '../../css/g/gxxk46bhj.css';
import '../../css/a/aeuiajbdn.css';
import '../../css/a/aycex6hon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bbxdvzjvn"/><path clip-rule="evenodd" class="ypdia9bkn"/><path class="gxxk46bhj"/><path class="aeuiajbdn"/><path class="aycex6hon"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:cloud-down-print" {...props}></Icon>
