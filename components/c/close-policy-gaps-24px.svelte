<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/alc186bpr.css';
import '../../css/s/s5iqn736v.css';
import '../../css/l/l65nnu6hm.css';
import '../../css/n/nqv10_xmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="alc186bpr"/><path class="s5iqn736v"/><path class="l65nnu6hm"/><path class="nqv10_xmu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:close-policy-gaps-24px" {...props}></Icon>
