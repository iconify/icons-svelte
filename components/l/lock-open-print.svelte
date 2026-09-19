<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d63otns7k.css';
import '../../css/a/a7cf72bwi.css';
import '../../css/u/ujauf4b7r.css';
import '../../css/x/xk51nbcmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="d63otns7k"/><path clip-rule="evenodd" class="a7cf72bwi"/><path clip-rule="evenodd" class="ujauf4b7r"/><path class="xk51nbcmj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:lock-open-print" {...props}></Icon>
