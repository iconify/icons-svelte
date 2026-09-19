<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/o/otizujbvg.css';
import '../../css/d/dmbuntb5b.css';
import '../../css/g/gxh6gnbgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="otizujbvg"/><path class="dmbuntb5b"/><path class="gxh6gnbgw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:drops-outline" {...props}></Icon>
