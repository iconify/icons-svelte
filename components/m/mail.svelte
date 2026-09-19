<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/c/ctq6evbba.css';
import '../../css/l/lh_zh7biy.css';
import '../../css/f/fri595bxy.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGl0YEsefU"><g class="ufeehvblu"><path class="ctq6evbba"/><path class="lh_zh7biy"/><path class="fri595bxy"/></g></mask></defs><path mask="url(#SVGl0YEsefU)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:mail" {...props}></Icon>
