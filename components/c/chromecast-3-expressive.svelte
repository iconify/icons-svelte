<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cp2yo5b1z.css';
import '../../css/b/b-gxn3boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="cp2yo5b1z"/><path class="b-gxn3boc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:chromecast-3-expressive" {...props}></Icon>
