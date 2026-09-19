<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aql7dnt-u.css';
import '../../css/e/ej4rzcb4e.css';
import '../../css/p/pa8fw9lpr.css';
import '../../css/k/kbwz4fv-v.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhMLTjd1r"><g class="aql7dnt-u"><path class="ej4rzcb4e"/><path class="pa8fw9lpr"/><path class="kbwz4fv-v"/></g></mask></defs><path mask="url(#SVGhMLTjd1r)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:market-analysis" {...props}></Icon>
