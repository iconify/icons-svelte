<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/x/xxb39ebcb.css';
import '../../css/k/kd4u92b_f.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGTrITfcYr"><g class="hv130ab-t"><path clip-rule="evenodd" class="xxb39ebcb"/><path class="kd4u92b_f"/></g></mask></defs><path mask="url(#SVGTrITfcYr)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:inner-shadow-down" {...props}></Icon>
