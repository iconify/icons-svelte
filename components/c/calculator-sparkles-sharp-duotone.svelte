<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/d/dj04zfbhi.css';
import '../../css/j/j8doxx_bn.css';
import '../../css/i/i645x0uvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dj04zfbhi"/><path class="j8doxx_bn"/><path class="i645x0uvs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:calculator-sparkles-sharp-duotone" {...props}></Icon>
