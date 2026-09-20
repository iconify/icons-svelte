<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d0f9rv80k.css';
import '../../css/l/l0-5eybmn.css';
import '../../css/k/kzx4hx4vr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="d0f9rv80k"/><path class="l0-5eybmn"/><path class="kzx4hx4vr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:database-duotone" {...props}></Icon>
