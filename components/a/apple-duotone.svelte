<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/q8ymr1bcw.css';
import '../../css/l/lsu2lbbmr.css';
import '../../css/i/itah7mg6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q8ymr1bcw"/><path class="lsu2lbbmr"/><path class="itah7mg6f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:apple-duotone" {...props}></Icon>
