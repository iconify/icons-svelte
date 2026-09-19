<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v1tummutu.css';
import '../../css/b/bcfxl-b2t.css';
import '../../css/g/gwasqepzs.css';
import '../../css/h/hpsmcoe0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="v1tummutu"/><path clip-rule="evenodd" class="bcfxl-b2t"/><path clip-rule="evenodd" class="gwasqepzs"/><path class="hpsmcoe0e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:pencil" {...props}></Icon>
