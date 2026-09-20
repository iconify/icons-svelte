<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/idqwhrbft.css';
import '../../css/k/kd3dk6bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="idqwhrbft"/><path clip-rule="evenodd" class="kd3dk6bth"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:nrksuper-avatar-expressive" {...props}></Icon>
