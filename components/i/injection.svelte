<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yqard8b1c.css';
import '../../css/e/edz9x2t2i.css';
import '../../css/x/xnj0lr11i.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4MNkIdef"><g class="ft5dv1b6b"><path clip-rule="evenodd" class="yqard8b1c"/><path class="edz9x2t2i"/><path class="xnj0lr11i"/></g></mask></defs><path mask="url(#SVG4MNkIdef)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:injection" {...props}></Icon>
