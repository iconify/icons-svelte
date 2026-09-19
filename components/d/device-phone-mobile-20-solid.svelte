<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qo5k08mbz.css';
import '../../css/s/svk051m5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="qo5k08mbz"/><path clip-rule="evenodd" class="svk051m5e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:device-phone-mobile-20-solid" {...props}></Icon>
