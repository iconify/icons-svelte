<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/evp8xsbel.css';
import '../../css/w/wu8w-7b0t.css';
import '../../css/l/lvwry-bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="evp8xsbel"/><path class="wu8w-7b0t"/><path class="lvwry-bxz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:box-duotone" {...props}></Icon>
