<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/h/hhhhlpzei.css';
import '../../css/i/i1m49fb9a.css';
import '../../css/l/lflp7ybyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="hhhhlpzei"/><path class="i1m49fb9a"/><path class="lflp7ybyo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:delivery" {...props}></Icon>
