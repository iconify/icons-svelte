<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hna7n1bsd.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/g/gjdm3pbxq.css';
import '../../css/w/wryprvbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="hna7n1bsd"/><g class="mc2zb0bvp"><path class="gjdm3pbxq"/><path class="wryprvbkm"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:quit-full-screen-bold-duotone" {...props}></Icon>
