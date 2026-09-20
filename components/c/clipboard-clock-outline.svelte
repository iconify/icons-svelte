<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/a5jpz2bqs.css';
import '../../css/h/h4-tcib6f.css';
import '../../css/k/k-cnudbay.css';
import '../../css/f/f0h52dh1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a5jpz2bqs"/><path class="h4-tcib6f"/><path class="k-cnudbay"/><path class="f0h52dh1e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-clock-outline" {...props}></Icon>
