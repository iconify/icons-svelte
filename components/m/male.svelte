<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/ai1nq5b5m.css';
import '../../css/a/a54vnbkrc.css';
import '../../css/r/r3s12lbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ai1nq5b5m"/><path class="a54vnbkrc"/><path class="r3s12lbsu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:male" {...props}></Icon>
