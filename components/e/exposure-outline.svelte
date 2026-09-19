<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xzf7mi7he.css';
import '../../css/h/hrlch2b6j.css';
import '../../css/z/zdrhem_xs.css';
import '../../css/r/ra0veia6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="xzf7mi7he"/><path clip-rule="evenodd" class="hrlch2b6j"/><path class="zdrhem_xs"/><path clip-rule="evenodd" class="ra0veia6x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:exposure-outline" {...props}></Icon>
