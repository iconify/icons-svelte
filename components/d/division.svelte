<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w2vq63b3k.css';
import '../../css/q/qufharbmm.css';
import '../../css/p/p9rvr-ggk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="w2vq63b3k"/><circle class="qufharbmm"/><circle class="p9rvr-ggk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:division" {...props}></Icon>
