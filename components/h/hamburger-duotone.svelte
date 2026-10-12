<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/j3y_v82fv.css';
import '../../css/n/nfz4ezbek.css';
import '../../css/r/r-r1vybtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="j3y_v82fv"/><path class="nfz4ezbek"/><path class="r-r1vybtq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hamburger-duotone" {...props}></Icon>
