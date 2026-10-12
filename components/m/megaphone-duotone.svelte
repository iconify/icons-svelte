<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p6ryabcru.css';
import '../../css/g/gkyrp556o.css';
import '../../css/h/haliu0b_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p6ryabcru"/><path class="gkyrp556o"/><path class="haliu0b_r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:megaphone-duotone" {...props}></Icon>
