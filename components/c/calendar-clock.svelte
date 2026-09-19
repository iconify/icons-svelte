<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/l/loml9rw7n.css';
import '../../css/y/yfausol3d.css';
import '../../css/b/bk7s47aiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="loml9rw7n"/><path class="yfausol3d"/><path class="bk7s47aiv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:calendar-clock" {...props}></Icon>
