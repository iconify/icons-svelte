<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/l/le8r1fb7t.css';
import '../../css/q/qfmv5tb9f.css';
import '../../css/k/kb5x2_bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="wwvp95byt"><path class="le8r1fb7t"/><path class="qfmv5tb9f"/><path class="kb5x2_bxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:bars-offset-2" {...props}></Icon>
