<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/s/sla-trbaw.css';
import '../../css/y/y56puac6x.css';
import '../../css/d/dmkk9tbyk.css';
import '../../css/a/auejspbti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="sla-trbaw"/><path class="y56puac6x"/><path class="dmkk9tbyk"/><path class="auejspbti"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:camera-outline" {...props}></Icon>
