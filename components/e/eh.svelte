<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/u/umbnhhb9z.css';
import '../../css/x/xnzk_khna.css';
import '../../css/r/r8actjfja.css';
import '../../css/z/zbnqi4l3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="umbnhhb9z"/><path class="xnzk_khna"/><path class="r8actjfja"/><path class="zbnqi4l3x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flagpack:eh" {...props}></Icon>
