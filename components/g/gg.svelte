<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/v/v-b0ev6uo.css';
import '../../css/u/ut5rdbbgx.css';
import '../../css/r/r0j41j0oh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="v-b0ev6uo"/><path class="ut5rdbbgx"/><path class="r0j41j0oh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:gg" {...props}></Icon>
