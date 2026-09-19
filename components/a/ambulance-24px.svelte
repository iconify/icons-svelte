<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/g-_iffbhm.css';
import '../../css/h/hezeheb9o.css';
import '../../css/n/ngc_fgbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g-_iffbhm"/><path clip-rule="evenodd" class="hezeheb9o"/><path class="ngc_fgbhq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ambulance-24px" {...props}></Icon>
