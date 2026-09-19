<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/y/ymsi6fbor.css';
import '../../css/i/idyp2ss1r.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<mask id="svgIDa"><g class="aql7dnt-u"><path clip-rule="evenodd" class="ymsi6fbor"/><path class="idyp2ss1r"/></g></mask><path mask="url(#svgIDa)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:behance" {...props}></Icon>
