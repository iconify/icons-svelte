<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vgyk2gmja.css';
import '../../css/f/fs4o0rlgx.css';
import '../../css/n/nc-hrj18w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vgyk2gmja"/><path class="fs4o0rlgx"/><path clip-rule="evenodd" class="nc-hrj18w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:donut-bitten-bold" {...props}></Icon>
