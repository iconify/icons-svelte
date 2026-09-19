<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/s/sedcd-iki.css';
import '../../css/g/gbrw6u1ww.css';
import '../../css/a/adk15x0vw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlbyQ8SSh"><g class="v3_i3wktz"><path class="sedcd-iki"/><path class="gbrw6u1ww"/><path class="adk15x0vw"/></g></mask></defs><path mask="url(#SVGlbyQ8SSh)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:flight-safety" {...props}></Icon>
