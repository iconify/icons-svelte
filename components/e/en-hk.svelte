<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/g/gp966mffb.css';
import '../../css/h/hrwcijwrl.css';
import '../../css/e/eo114u_wk.css';
import '../../css/e/eec2tedcw.css';
import '../../css/y/yvjv1pirb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="gp966mffb"/><path class="hrwcijwrl"/><path class="eo114u_wk"/><path class="eec2tedcw"/><path class="yvjv1pirb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:en-hk" {...props}></Icon>
