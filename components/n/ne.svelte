<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/q/qp5p3d7zu.css';
import '../../css/c/c_i9pnxhr.css';
import '../../css/i/i1bqeia1p.css';
import '../../css/f/fhafydb4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="qp5p3d7zu"/><path class="c_i9pnxhr"/><path class="i1bqeia1p"/><circle class="fhafydb4c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:ne" {...props}></Icon>
