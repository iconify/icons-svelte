<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/d/dcxavdy0e.css';
import '../../css/r/rlhd26bov.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSVLjOcsa"><g class="hv130ab-t"><path class="dcxavdy0e"/><path class="rlhd26bov"/></g></mask></defs><path mask="url(#SVGSVLjOcsa)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:optimize" {...props}></Icon>
