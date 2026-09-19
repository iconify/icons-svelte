<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nhxp2qbof.css';
import '../../css/g/gmf6vccax.css';
import '../../css/s/svv-jlbua.css';
import '../../css/v/vb2jx8bzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="nhxp2qbof"/><path clip-rule="evenodd" class="gmf6vccax"/><path class="svv-jlbua"/><path clip-rule="evenodd" class="vb2jx8bzd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:exclamation-triangle-outline" {...props}></Icon>
