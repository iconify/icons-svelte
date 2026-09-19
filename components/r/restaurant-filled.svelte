<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w_be9h43v.css';
import '../../css/u/us72j3bwj.css';
import '../../css/d/d-kiarazk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="w_be9h43v"/><path clip-rule="evenodd" class="us72j3bwj"/><path class="d-kiarazk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:restaurant-filled" {...props}></Icon>
