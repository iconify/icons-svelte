<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/a/aqa5dpbyw.css';
import '../../css/y/y3-2rob4h.css';
import '../../css/r/r_pad0b5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="aqa5dpbyw"/><path class="y3-2rob4h"/><path class="r_pad0b5k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:change" {...props}></Icon>
