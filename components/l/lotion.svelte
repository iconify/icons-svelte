<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/y/y5f1ucbki.css';
import '../../css/z/zfouoybeb.css';
import '../../css/c/c8tjlaclr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="y5f1ucbki"/><path class="zfouoybeb"/><path class="c8tjlaclr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:lotion" {...props}></Icon>
