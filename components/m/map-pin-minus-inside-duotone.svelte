<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uagohvbgi.css';
import '../../css/l/lvrgj0b6p.css';
import '../../css/u/ul6zk388y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uagohvbgi"/><path class="lvrgj0b6p"/><path class="ul6zk388y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:map-pin-minus-inside-duotone" {...props}></Icon>
