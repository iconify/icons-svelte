<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vcl_vm3gu.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/e/e6j6dgbiz.css';
import '../../css/m/mgnw8cbbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vcl_vm3gu"/><g class="mc2zb0bvp"><path class="e6j6dgbiz"/><path class="mgnw8cbbw"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:magnet-bold-duotone" {...props}></Icon>
