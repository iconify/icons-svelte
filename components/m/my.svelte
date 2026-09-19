<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/j/j29qogbvy.css';
import '../../css/v/vqdqihuwl.css';
import '../../css/i/i7s2upniq.css';
import '../../css/l/lgsipkbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="j29qogbvy"/><path class="vqdqihuwl"/><path class="i7s2upniq"/><path class="lgsipkbuk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:my" {...props}></Icon>
