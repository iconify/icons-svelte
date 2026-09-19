<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/x/xltgi6s1j.css';
import '../../css/l/l7hhb1bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="xltgi6s1j"/><path class="l7hhb1bii"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:camp" {...props}></Icon>
