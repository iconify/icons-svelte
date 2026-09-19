<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/c/c6jtjthhk.css';
import '../../css/f/fcu8rib6g.css';
import '../../css/n/ntbo-qb0z.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzvT79cfR"><g class="ufeehvblu"><path class="c6jtjthhk"/><path class="fcu8rib6g"/><path class="ntbo-qb0z"/></g></mask></defs><path mask="url(#SVGzvT79cfR)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:alarm-clock" {...props}></Icon>
