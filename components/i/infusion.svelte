<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/a/a4fw-bcwn.css';
import '../../css/b/buzi5ibmp.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGP6gv1bnK"><g class="v3_i3wktz"><path class="a4fw-bcwn"/><path class="buzi5ibmp"/></g></mask></defs><path mask="url(#SVGP6gv1bnK)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:infusion" {...props}></Icon>
