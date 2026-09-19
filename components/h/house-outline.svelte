<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f5k9ujbll.css';
import '../../css/d/dj61l2blf.css';
import '../../css/s/s2qm3rbjc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="f5k9ujbll"/><path clip-rule="evenodd" class="dj61l2blf"/><path class="s2qm3rbjc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:house-outline" {...props}></Icon>
