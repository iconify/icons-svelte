<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csw0kbbpv.css';
import '../../css/w/w9z9w7vpq.css';
import '../../css/i/i4qw-qb-a.css';
import '../../css/h/ha6ohkbrc.css';
import '../../css/x/xk412fbxm.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPeqL2bLi"><g class="csw0kbbpv"><path class="w9z9w7vpq"/><path class="i4qw-qb-a"/><path class="ha6ohkbrc"/><path class="xk412fbxm"/></g></mask></defs><path mask="url(#SVGPeqL2bLi)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:high-speed-rail" {...props}></Icon>
