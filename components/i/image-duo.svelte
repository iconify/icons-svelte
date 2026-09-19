<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iq9dzactc.css';
import '../../css/o/ohj00hbiv.css';
import '../../css/n/nrwtu07fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="iq9dzactc"/><path class="ohj00hbiv"/><path class="nrwtu07fj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:image-duo" {...props}></Icon>
