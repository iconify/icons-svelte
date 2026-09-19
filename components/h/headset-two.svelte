<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/q/q2cgsdcxn.css';
import '../../css/k/k7sl3bboy.css';
import '../../css/t/ty8kmubdm.css';
import '../../css/l/lxqcwwbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="q2cgsdcxn"/><path class="k7sl3bboy"/><path class="ty8kmubdm"/><path class="lxqcwwbex"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:headset-two" {...props}></Icon>
