<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/m/mcno18bmy.css';
import '../../css/i/i92g2uadp.css';
import '../../css/v/vsloccbcs.css';
import '../../css/g/gqdm7qboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><g class="mc2zb0bvp"><path class="mcno18bmy"/><path class="i92g2uadp"/></g><path class="vsloccbcs"/><path class="gqdm7qboe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevrons-left-right-bold-duotone" {...props}></Icon>
