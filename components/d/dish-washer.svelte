<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/f/feqkhlenc.css';
import '../../css/m/m2rrqgazx.css';
import '../../css/r/rkoylwbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="feqkhlenc"/><path class="m2rrqgazx"/><path class="rkoylwbig"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dish-washer" {...props}></Icon>
