<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/d/dxeb_oimn.css';
import '../../css/t/tvvrxbc0k.css';
import '../../css/j/j5lsn12so.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="dxeb_oimn"/><path class="tvvrxbc0k"/><path class="j5lsn12so"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:lotus" {...props}></Icon>
