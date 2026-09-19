<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/qj1iru8vv.css';
import '../../css/t/tn42p5bue.css';
import '../../css/r/rzggd57gx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="qj1iru8vv"/><path class="tn42p5bue"/><circle transform="matrix(-1 0 0 1 20 2.5)" class="rzggd57gx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mouse-right-click-02" {...props}></Icon>
