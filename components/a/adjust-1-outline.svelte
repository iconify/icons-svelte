<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/i/i65b-zb5p.css';
import '../../css/c/c94wgvbbu.css';
import '../../css/i/icvgb0jgu.css';
import '../../css/h/hb6grdbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="i65b-zb5p"/><path class="c94wgvbbu"/><path class="icvgb0jgu"/><path class="hb6grdbys"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:adjust-1-outline" {...props}></Icon>
