<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/kaxlnzbpc.css';
import '../../css/s/sjprw7bfy.css';
import '../../css/n/ngc_fgbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kaxlnzbpc"/><path clip-rule="evenodd" class="sjprw7bfy"/><path class="ngc_fgbhq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ambulance-outline-24px" {...props}></Icon>
