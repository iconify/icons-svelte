<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dm6lxrfug.css';
import '../../css/n/n94865b_n.css';
import '../../css/f/fbiosebgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="dm6lxrfug"/><path clip-rule="evenodd" class="n94865b_n"/><path class="fbiosebgy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:pin-bold" {...props}></Icon>
