<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/gxkg2nglx.css';
import '../../css/i/i20bt5bjj.css';
import '../../css/t/tqj-zy2in.css';
import '../../css/b/bm6komber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gxkg2nglx"/><path class="i20bt5bjj"/><path class="tqj-zy2in"/><path class="bm6komber"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:ai-vision-recognition" {...props}></Icon>
