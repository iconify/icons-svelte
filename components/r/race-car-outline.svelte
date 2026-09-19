<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f_fmg342a.css';
import '../../css/w/wvmwq-yxg.css';
import '../../css/u/ua-ukmbpm.css';
import '../../css/c/c019ivbij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="f_fmg342a"/><path clip-rule="evenodd" class="wvmwq-yxg"/><path class="ua-ukmbpm"/><path clip-rule="evenodd" class="c019ivbij"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:race-car-outline" {...props}></Icon>
