<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vihlqctim.css';
import '../../css/n/n_mwznbih.css';
import '../../css/o/oh3b46blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="vihlqctim"/><path clip-rule="evenodd" class="n_mwznbih"/><path class="oh3b46blr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:crosshairs-bold" {...props}></Icon>
