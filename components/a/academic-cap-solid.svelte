<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/ck9a2y9bt.css';
import '../../css/h/hyklb6qnw.css';
import '../../css/t/tq2ype9_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ck9a2y9bt"/><path class="hyklb6qnw"/><path class="tq2ype9_z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:academic-cap-solid" {...props}></Icon>
