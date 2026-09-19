<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/e/e5rjm3bsx.css';
import '../../css/a/azrk7m73e.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG7dOEjdFE"><g class="v3_i3wktz"><path class="e5rjm3bsx"/><path class="azrk7m73e"/></g></mask></defs><path mask="url(#SVG7dOEjdFE)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:full-selection" {...props}></Icon>
