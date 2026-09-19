<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/x/xxykgd7yr.css';
import '../../css/c/c5n1bc1jx.css';
import '../../css/a/axe9dpbxf.css';
import '../../css/e/eo6dyjn3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="xxykgd7yr"/><path class="c5n1bc1jx"/><path class="axe9dpbxf"/><path class="eo6dyjn3r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:gt" {...props}></Icon>
