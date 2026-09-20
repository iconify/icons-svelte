<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c--ct8_wq.css';
import '../../css/l/lawdo_brr.css';
import '../../css/k/kkl9unbzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c--ct8_wq"/><path class="lawdo_brr"/><path class="kkl9unbzu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:code-outline" {...props}></Icon>
