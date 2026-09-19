<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wete5r8ng.css';
import '../../css/b/bvox4ywgs.css';
import '../../css/b/buj03-bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="wete5r8ng"/><path class="bvox4ywgs"/><path class="buj03-bwd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:crown-1-bold" {...props}></Icon>
