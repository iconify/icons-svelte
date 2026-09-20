<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/b/bporwpv9i.css';
import '../../css/u/ujw8tpbuy.css';
import '../../css/c/cbby56vwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="bporwpv9i"/><path class="ujw8tpbuy"/><path class="cbby56vwn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:clipboard-paste" {...props}></Icon>
