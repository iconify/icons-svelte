<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/jygacmrnh.css';
import '../../css/m/my21gqwam.css';
import '../../css/b/b7a5s8hvw.css';
import '../../css/q/qmoed6b2h.css';
import '../../css/t/tiez6k3bz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="jygacmrnh"/><path class="my21gqwam"/><path class="b7a5s8hvw"/><path class="qmoed6b2h"/><path class="tiez6k3bz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:qr-code" {...props}></Icon>
