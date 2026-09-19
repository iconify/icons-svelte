<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6p0_bl_n.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWJIstexD"><path class="v6p0_bl_n"/></mask></defs><path mask="url(#SVGWJIstexD)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:lightning" {...props}></Icon>
