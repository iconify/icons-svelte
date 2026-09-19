<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/u/udkgazzrc.css';
import '../../css/o/o-hsaebns.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGr33dnebo"><g class="v3_i3wktz"><path class="udkgazzrc"/><path class="o-hsaebns"/></g></mask></defs><path mask="url(#SVGr33dnebo)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:high-light" {...props}></Icon>
