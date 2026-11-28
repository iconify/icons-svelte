<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/e_a7e9bfr.css';
import '../../css/m/mtvc7cmli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e_a7e9bfr secondary"/><path class="mtvc7cmli primary"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:low-bandwidth-needle-duotone" {...props}></Icon>
