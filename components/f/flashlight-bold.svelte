<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/r1q0bcchq.css';
import '../../css/o/o9unslmnw.css';
import '../../css/l/lt6ufqbxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r1q0bcchq"/><path class="o9unslmnw"/><path clip-rule="evenodd" class="lt6ufqbxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:flashlight-bold" {...props}></Icon>
