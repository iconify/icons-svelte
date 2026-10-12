<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vk43r2bac.css';
import '../../css/g/gis6iufnu.css';
import '../../css/w/w0-ba4bwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="vk43r2bac"/><path class="gis6iufnu"/><path class="w0-ba4bwd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:brush-duotone" {...props}></Icon>
