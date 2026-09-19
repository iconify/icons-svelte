<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/u/ucionx-lv.css';
import '../../css/y/ybxw_bc8q.css';
import '../../css/i/id7402b9s.css';
import '../../css/a/ayju-qj-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ufeehvblu"><path class="ucionx-lv"/><ellipse class="ybxw_bc8q"/><path class="id7402b9s"/><path class="ayju-qj-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:music-list" {...props}></Icon>
