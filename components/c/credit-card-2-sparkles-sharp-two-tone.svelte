<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/w/w0d5lhbyf.css';
import '../../css/u/uecn1lb3p.css';
import '../../css/q/q3vaf6zlj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="w0d5lhbyf"/><path class="uecn1lb3p"/><path class="q3vaf6zlj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:credit-card-2-sparkles-sharp-two-tone" {...props}></Icon>
