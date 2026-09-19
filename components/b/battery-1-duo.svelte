<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qs8_8gyor.css';
import '../../css/c/cwxewbz_z.css';
import '../../css/z/zqsykkb_l.css';
import '../../css/v/vsj6npbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="qs8_8gyor"/><path class="cwxewbz_z"/><path class="zqsykkb_l"/><path class="vsj6npbjq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-1-duo" {...props}></Icon>
