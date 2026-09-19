<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/j-v2u4nhg.css';
import '../../css/k/ktq9h8bpb.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG14S4vcdA"><g class="v3_i3wktz"><path class="j-v2u4nhg"/><path class="ktq9h8bpb"/></g></mask></defs><path mask="url(#SVG14S4vcdA)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:loudly-crying-face-whit-open-mouth" {...props}></Icon>
