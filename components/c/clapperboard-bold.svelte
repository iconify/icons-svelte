<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/ra3icybqn.css';
import '../../css/w/w7wbu5bna.css';
import '../../css/f/f4d5x_t8i.css';
import '../../css/c/cvilxkbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ra3icybqn"/><path class="w7wbu5bna"/><path class="f4d5x_t8i"/><path class="cvilxkbqn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clapperboard-bold" {...props}></Icon>
