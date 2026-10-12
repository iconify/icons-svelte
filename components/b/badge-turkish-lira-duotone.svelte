<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g79xbo1hg.css';
import '../../css/i/ijgp7yb3n.css';
import '../../css/f/fbyge-9ve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g79xbo1hg"/><path class="ijgp7yb3n"/><path class="fbyge-9ve"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:badge-turkish-lira-duotone" {...props}></Icon>
