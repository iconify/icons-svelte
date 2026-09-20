<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/luy9z6pgm.css';
import '../../css/e/ehvke5qnp.css';
import '../../css/a/am157rupi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="luy9z6pgm"/><path class="ehvke5qnp"/><path clip-rule="evenodd" class="am157rupi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:nightstand4-filled" {...props}></Icon>
