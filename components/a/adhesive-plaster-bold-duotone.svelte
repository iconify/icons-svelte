<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/bkgvjbbfd.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/l/lkzock2wt.css';
import '../../css/p/p4n3pmbrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bkgvjbbfd"/><g class="mc2zb0bvp"><path class="lkzock2wt"/><path class="p4n3pmbrj"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:adhesive-plaster-bold-duotone" {...props}></Icon>
