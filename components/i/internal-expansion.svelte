<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/e/e0pazubmt.css';
import '../../css/s/si5nizbso.css';
import '../../css/w/w19wwz2kz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="e0pazubmt"/><path clip-rule="evenodd" class="si5nizbso"/><path class="w19wwz2kz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:internal-expansion" {...props}></Icon>
