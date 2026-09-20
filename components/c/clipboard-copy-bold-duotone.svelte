<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mnu832bbh.css';
import '../../css/c/c3lyyzb8p.css';
import '../../css/x/xam49m99q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mnu832bbh"/><path class="c3lyyzb8p"/><path class="xam49m99q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-copy-bold-duotone" {...props}></Icon>
