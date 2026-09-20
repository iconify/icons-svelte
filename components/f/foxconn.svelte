<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_r_9v7-z.css';
import '../../css/f/ferjt9b2f.css';
import '../../css/g/g37okb3zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":378,"height":81};
const content = `<mask id="SVGLnHLMeNR" width="378" height="81" x="0" y="0" maskUnits="userSpaceOnUse" style="mask-type:luminance"><path class="a_r_9v7-z"/></mask><g mask="url(#SVGLnHLMeNR)" class="ferjt9b2f"><path class="g37okb3zn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:foxconn" {...props}></Icon>
