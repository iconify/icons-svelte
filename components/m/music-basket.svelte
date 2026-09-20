<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xjdos9exn.css';
import '../../css/o/ohpbju5jc.css';
import '../../css/d/dag-dkc4k.css';
import '../../css/y/yogb4gebd.css';
import '../../css/s/s5kxay-fy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xjdos9exn"/><path class="ohpbju5jc"/><path class="dag-dkc4k"/><path class="yogb4gebd"/><path class="s5kxay-fy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:music-basket" {...props}></Icon>
