<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/nopuubb8w.css';
import '../../css/x/xke9tubde.css';
import '../../css/c/c86udab-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="nopuubb8w"/><path class="xke9tubde"/><path class="c86udab-t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bitcoin-location" {...props}></Icon>
