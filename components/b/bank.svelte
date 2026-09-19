<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/c/c-bbc_bpd.css';
import '../../css/c/c5g7-u9cc.css';
import '../../css/l/l54so-d8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="c-bbc_bpd"/><path class="c5g7-u9cc"/><path class="l54so-d8u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bank" {...props}></Icon>
