<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adexpl72i.css';
import '../../css/a/aqezq3b2u.css';
import '../../css/g/go_3kbx3s.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGVB2dqNmI"><g class="adexpl72i"><path class="aqezq3b2u"/><path clip-rule="evenodd" class="go_3kbx3s"/></g></mask></defs><path mask="url(#SVGVB2dqNmI)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:circle-three" {...props}></Icon>
