<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fr7h38bjf.css';
import '../../css/e/ef6l1eg-m.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGyssyseA"><g class="v3_i3wktz"><path class="fr7h38bjf"/><path class="ef6l1eg-m"/></g></mask></defs><path mask="url(#SVGGyssyseA)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:pagoda" {...props}></Icon>
