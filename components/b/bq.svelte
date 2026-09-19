<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/d/dlejmac_f.css';
import '../../css/i/iadlwcc0p.css';
import '../../css/p/pbejrrbtb.css';
import '../../css/z/zdgvfvbkv.css';
import '../../css/r/r66aynbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGuywqVbel"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGuywqVbel)"><path class="dlejmac_f"/><path class="iadlwcc0p"/><path class="pbejrrbtb"/><path class="zdgvfvbkv"/><path class="r66aynbmu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:bq" {...props}></Icon>
