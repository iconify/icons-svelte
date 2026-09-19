<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/g/g8ciazbyu.css';
import '../../css/d/dmtq6nxpb.css';
import '../../css/u/u7cx-4fdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="g8ciazbyu"/><path class="dmtq6nxpb"/><path class="u7cx-4fdn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:pineapple" {...props}></Icon>
