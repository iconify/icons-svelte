<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n9m870bof.css';
import '../../css/g/go72okfmy.css';
import '../../css/n/nbj4kcceg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="n9m870bof"/><path class="go72okfmy"/><rect class="nbj4kcceg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:comment-3" {...props}></Icon>
