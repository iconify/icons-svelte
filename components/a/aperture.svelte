<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dyk91zota.css';
import '../../css/c/cp4lmky5m.css';
import '../../css/k/khl_6qbmw.css';
import '../../css/j/jsr00m3kj.css';
import '../../css/w/wcj-r41ni.css';
import '../../css/e/er4khtape.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dyk91zota"/><path class="cp4lmky5m"/><path class="khl_6qbmw"/><path class="jsr00m3kj"/><path class="wcj-r41ni"/><path class="er4khtape"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:aperture" {...props}></Icon>
