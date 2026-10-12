<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fqj1yfbwj.css';
import '../../css/f/fbyge-9ve.css';
import '../../css/a/ai741630p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fqj1yfbwj"/><path class="fbyge-9ve"/><path class="ai741630p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:badge-minus-duotone" {...props}></Icon>
