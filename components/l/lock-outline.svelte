<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/v/vkdb8v_jn.css';
import '../../css/v/v6g0_ypjy.css';
import '../../css/u/uvl5k5lzm.css';
import '../../css/x/xu8bgpb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="vkdb8v_jn"/><path class="v6g0_ypjy"/><path class="uvl5k5lzm"/><path class="xu8bgpb2t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:lock-outline" {...props}></Icon>
