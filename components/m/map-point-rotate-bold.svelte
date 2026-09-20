<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/b/b60eo5bxw.css';
import '../../css/i/i_hca-bhh.css';
import '../../css/f/fno7as3wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b60eo5bxw"/><path class="i_hca-bhh"/><path clip-rule="evenodd" class="fno7as3wa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-point-rotate-bold" {...props}></Icon>
