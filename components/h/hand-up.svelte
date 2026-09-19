<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/k/ka6c5cbmx.css';
import '../../css/p/puckv5bwn.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgzUlicSd"><g class="v3_i3wktz"><path class="ka6c5cbmx"/><path clip-rule="evenodd" class="puckv5bwn"/></g></mask></defs><path mask="url(#SVGgzUlicSd)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:hand-up" {...props}></Icon>
