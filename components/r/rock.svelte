<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/p/pa5opcbgo.css';
import '../../css/p/pvbrq0iat.css';
import '../../css/j/jlvcoldrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="pa5opcbgo"/><path class="pvbrq0iat"/><path class="jlvcoldrg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:rock" {...props}></Icon>
