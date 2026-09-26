<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rz8ra2brm.css';
import '../../css/v/vik802c-d.css';
import '../../css/q/q_s83rbme.css';
import '../../css/o/obh0-9ban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="rz8ra2brm"/><path class="vik802c-d"/><path class="q_s83rbme"/><path class="obh0-9ban"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:columns-3-cog-bold-duotone" {...props}></Icon>
