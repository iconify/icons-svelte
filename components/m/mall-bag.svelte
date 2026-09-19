<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/jm8jfs5cr.css';
import '../../css/d/de8dzpspb.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGmGuvjbTO"><g class="v3_i3wktz"><path class="jm8jfs5cr"/><path class="de8dzpspb"/></g></mask></defs><path mask="url(#SVGmGuvjbTO)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:mall-bag" {...props}></Icon>
