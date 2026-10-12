<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bmv2fpbdp.css';
import '../../css/p/pv9ynuz7u.css';
import '../../css/g/gfrp25f_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bmv2fpbdp"/><path class="pv9ynuz7u"/><path class="gfrp25f_d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:notebook-tabs-duotone" {...props}></Icon>
