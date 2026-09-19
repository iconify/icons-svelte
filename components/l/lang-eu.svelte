<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/h/heo1q5uyj.css';
import '../../css/m/m3xu1ldqr.css';
import '../../css/q/qzb3rzbwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGuywqVbel"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGuywqVbel)"><path class="heo1q5uyj"/><path class="m3xu1ldqr"/><path class="qzb3rzbwv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:lang-eu" {...props}></Icon>
