<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/tyyc_hb3b.css';
import '../../css/k/kgb_qyblb.css';
import '../../css/r/r3xj1zbve.css';
import '../../css/w/wphsgxkzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="tyyc_hb3b"/><path class="kgb_qyblb"/><circle class="r3xj1zbve"/><path class="wphsgxkzu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:estimate-02" {...props}></Icon>
