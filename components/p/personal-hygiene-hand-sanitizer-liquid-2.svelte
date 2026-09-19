<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/h/hlim-4b5l.css';
import '../../css/b/bx9kiqocv.css';
import '../../css/l/lkp8d_bfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hlim-4b5l"/><path class="bx9kiqocv"/><path class="lkp8d_bfq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:personal-hygiene-hand-sanitizer-liquid-2" {...props}></Icon>
