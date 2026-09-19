<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qs8_8gyor.css';
import '../../css/o/oluiti4kl.css';
import '../../css/z/zqsykkb_l.css';
import '../../css/y/yz4e_lbwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="qs8_8gyor"/><path class="oluiti4kl"/><path class="zqsykkb_l"/><path class="yz4e_lbwb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:battery-4-duo" {...props}></Icon>
