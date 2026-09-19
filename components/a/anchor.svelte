<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g3fz5ybsb.css';
import '../../css/v/vnhubhthd.css';
import '../../css/f/fkas6vb7y.css';
import '../../css/v/vek4heose.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="g3fz5ybsb"/><path class="vnhubhthd"/><path class="fkas6vb7y"/><path class="vek4heose"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:anchor" {...props}></Icon>
