<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc1fd0lxe.css';
import '../../css/c/cth2izb7y.css';
import '../../css/d/d2t-0cbdb.css';
import '../../css/x/xbm6mjgvm.css';
import '../../css/e/ewteercny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<mask id="SVGqdEcMdXs"><circle class="bc1fd0lxe"/></mask><g mask="url(#SVGqdEcMdXs)"><path class="cth2izb7y"/><path class="d2t-0cbdb"/><path class="xbm6mjgvm"/><path class="ewteercny"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circle-flags:mu" {...props}></Icon>
