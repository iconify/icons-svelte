<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jadh4hbzm.css';
import '../../css/y/y6qmidbva.css';
import '../../css/h/hsm64gbpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="jadh4hbzm"/><path class="y6qmidbva"/><path class="hsm64gbpu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cloud-sun-2-bold" {...props}></Icon>
