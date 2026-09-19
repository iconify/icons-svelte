<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pz2uyujao.css';
import '../../css/f/fj61g7l0m.css';
import '../../css/e/el7ev0b3z.css';
import '../../css/m/m_1h3hg9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="pz2uyujao"/><path clip-rule="evenodd" class="fj61g7l0m"/><path class="el7ev0b3z"/><path clip-rule="evenodd" class="m_1h3hg9s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:layout-2-outline" {...props}></Icon>
