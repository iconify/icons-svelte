<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/l/ly7322hhe.css';
import '../../css/n/nts83s09d.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG17ZTkeUO"><g class="v3_i3wktz"><path class="ly7322hhe"/><path clip-rule="evenodd" class="nts83s09d"/></g></mask></defs><path mask="url(#SVG17ZTkeUO)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:hand-right" {...props}></Icon>
