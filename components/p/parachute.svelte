<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/g/gh28gsjwe.css';
import '../../css/f/fm_ve5bbr.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGjj1J1bLL"><g class="v3_i3wktz"><path class="gh28gsjwe"/><path class="fm_ve5bbr"/></g></mask></defs><path mask="url(#SVGjj1J1bLL)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:parachute" {...props}></Icon>
