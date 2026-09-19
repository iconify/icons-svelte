<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/r/rkrcdf-xu.css';
import '../../css/q/qf59tfblw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGIcZXicPl"><g class="v3_i3wktz"><path class="rkrcdf-xu"/><path class="qf59tfblw"/></g></mask></defs><path mask="url(#SVGIcZXicPl)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:airplay" {...props}></Icon>
