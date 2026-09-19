<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fbxmsfbue.css';
import '../../css/w/w17uzvbov.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGFpN5cc0d"><g class="ft5dv1b6b"><rect class="fbxmsfbue"/><path class="w17uzvbov"/></g></mask></defs><path mask="url(#SVGFpN5cc0d)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:direction" {...props}></Icon>
