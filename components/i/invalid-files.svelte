<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/x/xh09az3_x.css';
import '../../css/i/iz9z3bilq.css';
import '../../css/m/m6xeubc1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="xh09az3_x"/><path class="iz9z3bilq"/><path class="m6xeubc1w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:invalid-files" {...props}></Icon>
