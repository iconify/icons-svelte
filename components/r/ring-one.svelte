<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/e/e10y7tc3x.css';
import '../../css/m/mfsd7w07b.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGo59oLpeP"><g class="v3_i3wktz"><path class="e10y7tc3x"/><path class="mfsd7w07b"/></g></mask></defs><path mask="url(#SVGo59oLpeP)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:ring-one" {...props}></Icon>
