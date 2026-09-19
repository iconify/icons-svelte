<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iitrv6b_u.css';
import '../../css/j/jeqnyebai.css';
import '../../css/p/pzp-sptxq.css';
import '../../css/r/r-n3tp3un.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="iitrv6b_u"><path class="jeqnyebai"/><path class="pzp-sptxq"/><path class="r-n3tp3un"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:cargo" {...props}></Icon>
