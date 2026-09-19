<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/r/ripdjiu2y.css';
import '../../css/k/kxpgxsbnl.css';
import '../../css/a/an0us4bhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="ripdjiu2y"/><path class="kxpgxsbnl"/><rect class="an0us4bhe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:bottle-three" {...props}></Icon>
