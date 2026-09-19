<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/e/e7lmpc1qb.css';
import '../../css/n/npiz6qlvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path clip-rule="evenodd" class="e7lmpc1qb"/><path class="npiz6qlvn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:hanger" {...props}></Icon>
