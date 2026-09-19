<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/v/v3v0unr3c.css';
import '../../css/f/f9s13obdp.css';
import '../../css/v/v-4_iy42m.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNqi2ydLJ"><g class="ufeehvblu"><path class="v3v0unr3c"/><path class="f9s13obdp"/><path class="v-4_iy42m"/></g></mask></defs><path mask="url(#SVGNqi2ydLJ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:full-selection" {...props}></Icon>
