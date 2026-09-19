<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/c/cp-yxsb5p.css';
import '../../css/m/m6257tb5b.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlifwpegN"><g class="v3_i3wktz"><path class="cp-yxsb5p"/><path class="m6257tb5b"/></g></mask></defs><path mask="url(#SVGlifwpegN)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:application-one" {...props}></Icon>
