<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/ww1487byk.css';
import '../../css/b/b6cjujs6z.css';
import '../../css/i/i2n_j2bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ww1487byk"/><path class="b6cjujs6z"/><path class="i2n_j2bus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:baseball-bat" {...props}></Icon>
