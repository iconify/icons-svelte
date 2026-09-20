<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cd54kqbft.css';
import '../../css/o/ojhz1pbpg.css';
import '../../css/g/gurbwkb6n.css';
import '../../css/g/gz30py4vu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cd54kqbft"/><path class="ojhz1pbpg"/><path class="gurbwkb6n"/><path class="gz30py4vu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:container-outline" {...props}></Icon>
