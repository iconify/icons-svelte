<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/x_ct48b7d.css';
import '../../css/x/xt05grelv.css';
import '../../css/c/couy49bzm.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMYzUucXz"><g class="v3_i3wktz"><path class="x_ct48b7d"/><path class="xt05grelv"/><path class="couy49bzm"/></g></mask></defs><path mask="url(#SVGMYzUucXz)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:inbox-success" {...props}></Icon>
