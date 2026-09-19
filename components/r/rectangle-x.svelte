<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/y/ye8ewzq1l.css';
import '../../css/z/ze8hslbqf.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSVFBbdlk"><g class="v3_i3wktz"><path class="ye8ewzq1l"/><path class="ze8hslbqf"/></g></mask></defs><path mask="url(#SVGSVFBbdlk)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:rectangle-x" {...props}></Icon>
