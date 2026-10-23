<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/prt4gzb-p.css';
import '../../css/m/mh0g7aczs.css';
import '../../css/m/m9b14vbcs.css';
import '../../css/b/bkfwo226r.css';
import '../../css/p/p6c6arbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="prt4gzb-p"/><path class="mh0g7aczs"/><path class="m9b14vbcs"/><path class="bkfwo226r"/><path class="p6c6arbow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:perfume-bottle-duotone" {...props}></Icon>
