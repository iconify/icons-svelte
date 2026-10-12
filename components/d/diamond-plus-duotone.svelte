<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/ygv4c4bdn.css';
import '../../css/n/nw4f7abft.css';
import '../../css/a/ai741630p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ygv4c4bdn"/><path class="nw4f7abft"/><path class="ai741630p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:diamond-plus-duotone" {...props}></Icon>
