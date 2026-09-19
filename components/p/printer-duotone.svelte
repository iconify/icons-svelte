<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p12dhibmp.css';
import '../../css/m/mdhqcyvse.css';
import '../../css/g/g2ef58b-q.css';
import '../../css/i/ik193tb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p12dhibmp"/><path class="mdhqcyvse"/><path class="g2ef58b-q"/><path class="ik193tb7c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:printer-duotone" {...props}></Icon>
