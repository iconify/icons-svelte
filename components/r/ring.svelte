<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/m/mv2y2abjm.css';
import '../../css/o/oftu6aboy.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGndQR5c2x"><g class="v3_i3wktz"><path class="mv2y2abjm"/><path class="oftu6aboy"/></g></mask></defs><path mask="url(#SVGndQR5c2x)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:ring" {...props}></Icon>
