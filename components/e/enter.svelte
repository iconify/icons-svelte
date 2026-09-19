<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to0c2ub7t.css';
import '../../css/p/pxigoteko.css';
import '../../css/n/n0z6nacxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="to0c2ub7t"><path clip-rule="evenodd" class="pxigoteko"/><path class="n0z6nacxt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:enter" {...props}></Icon>
