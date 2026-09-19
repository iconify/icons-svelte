<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/x/x-g9jw6ft.css';
import '../../css/g/gi5qaabdi.css';
import '../../css/w/w7kf1r9jw.css';
import '../../css/f/fve0_hbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="x-g9jw6ft"/><rect class="gi5qaabdi"/><path class="w7kf1r9jw"/><path class="fve0_hbpg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:basketball-clothes" {...props}></Icon>
