<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/x/xi8f7-cfb.css';
import '../../css/y/y8j_hsb4g.css';
import '../../css/m/mbpirf25d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="xi8f7-cfb"/><path class="y8j_hsb4g"/><path class="mbpirf25d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:ir" {...props}></Icon>
