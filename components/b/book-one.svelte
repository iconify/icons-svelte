<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/xaf8zqb-s.css';
import '../../css/r/rie76vbte.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG0DcpHc9l"><g class="v3_i3wktz"><path class="xaf8zqb-s"/><path class="rie76vbte"/></g></mask></defs><path mask="url(#SVG0DcpHc9l)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:book-one" {...props}></Icon>
