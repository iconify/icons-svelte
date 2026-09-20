<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7fmnlb4r.css';
import '../../css/z/zwp91acod.css';
import '../../css/z/zwb14lhyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="j7fmnlb4r"><path class="zwp91acod"/><path class="zwb14lhyy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:key-line" {...props}></Icon>
