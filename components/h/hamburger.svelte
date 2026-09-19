<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/l/lwc-i7bqs.css';
import '../../css/y/ysooycc-h.css';
import '../../css/j/jytgr1bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path clip-rule="evenodd" class="lwc-i7bqs"/><path class="ysooycc-h"/><path class="jytgr1bls"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:hamburger" {...props}></Icon>
