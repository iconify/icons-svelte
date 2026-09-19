<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7mn_xgnv.css';
import '../../css/o/oojk4pbmj.css';
import '../../css/y/ytntd_8jh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="h7mn_xgnv"><path class="oojk4pbmj"/><path class="ytntd_8jh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:border-outer-outline" {...props}></Icon>
