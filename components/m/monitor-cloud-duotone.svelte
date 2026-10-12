<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ijmo84y7j.css';
import '../../css/u/uzmwkhbts.css';
import '../../css/z/zb2v6-b5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ijmo84y7j"/><path class="uzmwkhbts"/><path clip-rule="evenodd" class="zb2v6-b5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:monitor-cloud-duotone" {...props}></Icon>
