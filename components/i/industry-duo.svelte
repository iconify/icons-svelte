<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hltyj8b6l.css';
import '../../css/c/ctk3_x4ut.css';
import '../../css/i/iq3e-sygp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="hltyj8b6l"/><path class="ctk3_x4ut"/><path class="iq3e-sygp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:industry-duo" {...props}></Icon>
