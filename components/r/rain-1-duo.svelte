<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/s6r_4vb3z.css';
import '../../css/c/cw47yzbif.css';
import '../../css/n/nm2wr6boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="s6r_4vb3z"/><path class="cw47yzbif"/><path class="nm2wr6boy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:rain-1-duo" {...props}></Icon>
