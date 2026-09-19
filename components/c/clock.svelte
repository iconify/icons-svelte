<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dzfunhbuj.css';
import '../../css/i/i1hn7158g.css';
import '../../css/s/s-5bh34nf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="dzfunhbuj"/><path class="i1hn7158g"/><path class="s-5bh34nf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:clock" {...props}></Icon>
