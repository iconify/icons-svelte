<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/j-v2u4nhg.css';
import '../../css/o/ojp9--njg.css';
import '../../css/k/krw5o0bvk.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGU1vDUb6k"><g class="v3_i3wktz"><path class="j-v2u4nhg"/><path class="ojp9--njg"/><path class="krw5o0bvk"/></g></mask></defs><path mask="url(#SVGU1vDUb6k)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:record-disc" {...props}></Icon>
