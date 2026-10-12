<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tnbdi8n3b.css';
import '../../css/i/i6u14jbud.css';
import '../../css/s/s8riu9c1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tnbdi8n3b"/><path class="i6u14jbud"/><path class="s8riu9c1v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:plug-zap-duotone" {...props}></Icon>
