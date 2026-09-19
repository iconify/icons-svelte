<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w9ol47byu.css';
import '../../css/n/n5-8jdgvs.css';
import '../../css/m/m7cme73nv.css';
import '../../css/j/j8qsfsb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="w9ol47byu"/><path class="n5-8jdgvs"/><path class="m7cme73nv"/><path class="j8qsfsb3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:kick-scooter-bold" {...props}></Icon>
