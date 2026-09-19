<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/d/dkifpkb7f.css';
import '../../css/e/ed0jdhbeg.css';
import '../../css/z/z6n0qjvfb.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtnDBWJ9A"><g class="v3_i3wktz"><path class="dkifpkb7f"/><path clip-rule="evenodd" class="ed0jdhbeg"/><path clip-rule="evenodd" class="z6n0qjvfb"/></g></mask></defs><path mask="url(#SVGtnDBWJ9A)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:nests" {...props}></Icon>
