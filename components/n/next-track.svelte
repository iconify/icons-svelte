<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/s/s37yj4b_i.css';
import '../../css/k/k5fwq_p9i.css';
import '../../css/a/a1y0dmlic.css';
import '../../css/b/bocuyrlcq.css';
import '../../css/b/bb1u2n-kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="s37yj4b_i"/><path clip-rule="evenodd" class="k5fwq_p9i"/><path class="a1y0dmlic"/><path clip-rule="evenodd" class="bocuyrlcq"/><path clip-rule="evenodd" class="bb1u2n-kn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:next-track" {...props}></Icon>
