<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv130ab-t.css';
import '../../css/u/ughwv1b5j.css';
import '../../css/b/bl47i_h6l.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEYElucub"><g class="hv130ab-t"><path class="ughwv1b5j"/><path class="bl47i_h6l"/></g></mask></defs><path mask="url(#SVGEYElucub)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:distribute-horizontal-spacing" {...props}></Icon>
