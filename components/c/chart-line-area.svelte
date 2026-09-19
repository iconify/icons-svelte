<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/o/oan152bkl.css';
import '../../css/v/v3sybybfr.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGG6xKxdRX"><g class="v3_i3wktz"><path class="oan152bkl"/><path class="v3sybybfr"/></g></mask></defs><path mask="url(#SVGG6xKxdRX)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:chart-line-area" {...props}></Icon>
