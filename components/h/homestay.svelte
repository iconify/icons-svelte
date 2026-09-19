<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/r/rrrrw5wgk.css';
import '../../css/b/b0jcdrlrj.css';
import '../../css/b/b44haw56m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="rrrrw5wgk"/><path class="b0jcdrlrj"/><path class="b44haw56m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:homestay" {...props}></Icon>
