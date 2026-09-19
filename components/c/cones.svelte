<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/a/ag1ho_ber.css';
import '../../css/d/dlx2xvbhm.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGyZTuDeEO"><g class="v3_i3wktz"><path class="ag1ho_ber"/><path class="dlx2xvbhm"/></g></mask></defs><path mask="url(#SVGyZTuDeEO)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:cones" {...props}></Icon>
