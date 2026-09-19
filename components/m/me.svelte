<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/p/pt-0x-bak.css';
import '../../css/a/az4l81ban.css';
import '../../css/l/lxj99hpsx.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGArhzCdfE"><g class="v3_i3wktz"><path clip-rule="evenodd" class="pt-0x-bak"/><path class="az4l81ban"/><path class="lxj99hpsx"/></g></mask></defs><path mask="url(#SVGArhzCdfE)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:me" {...props}></Icon>
