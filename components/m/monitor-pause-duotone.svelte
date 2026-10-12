<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kjyb9ab8t.css';
import '../../css/y/yjlljib5h.css';
import '../../css/k/ks1ls910s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kjyb9ab8t"/><path class="yjlljib5h"/><path class="ks1ls910s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:monitor-pause-duotone" {...props}></Icon>
