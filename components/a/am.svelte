<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/f/ftcyrvb-q.css';
import '../../css/b/bwdxsg6jt.css';
import '../../css/t/t4wur0y1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="ftcyrvb-q"/><path class="bwdxsg6jt"/><path class="t4wur0y1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:am" {...props}></Icon>
