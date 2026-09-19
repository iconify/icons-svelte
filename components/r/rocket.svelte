<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/q/qdychfmlx.css';
import '../../css/f/fsqn6obci.css';
import '../../css/d/dak5wlciw.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGDsP4Cect"><g class="v3_i3wktz"><path class="qdychfmlx"/><path clip-rule="evenodd" class="fsqn6obci"/><path class="dak5wlciw"/></g></mask></defs><path mask="url(#SVGDsP4Cect)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:rocket" {...props}></Icon>
