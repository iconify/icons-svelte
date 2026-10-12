<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lh4_-wb-l.css';
import '../../css/b/bussztgsc.css';
import '../../css/i/ivyiakb7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lh4_-wb-l"/><path class="bussztgsc"/><path class="ivyiakb7x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:align-horizontal-distribute-start-duotone" {...props}></Icon>
