<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/f/fp5szcbjl.css';
import '../../css/u/uu4naqb6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<g class="n1lsf0bnc"><path class="fp5szcbjl"/><path class="uu4naqb6f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:dashboard" {...props}></Icon>
