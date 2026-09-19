<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy-g5sp0v.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZZ153dkC"><path class="gy-g5sp0v"/></mask></defs><path mask="url(#SVGZZ153dkC)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:page-template" {...props}></Icon>
