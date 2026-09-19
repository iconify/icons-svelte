<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xvs_6lz2b.css';
import '../../css/z/z-u_4v9zs.css';
import '../../css/f/ftcbseb_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="xvs_6lz2b"/><path class="z-u_4v9zs"/><path class="ftcbseb_g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:info-circle" {...props}></Icon>
