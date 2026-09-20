<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wq0hmuiej.css';
import '../../css/z/znucjgzav.css';
import '../../css/b/bn6w8zb9h.css';
import '../../css/q/qj1hodctu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wq0hmuiej"/><path class="znucjgzav"/><path clip-rule="evenodd" class="bn6w8zb9h"/><path class="qj1hodctu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clapperboard-open-play-bold" {...props}></Icon>
