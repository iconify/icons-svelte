<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qqm0zqpjw.css';
import '../../css/r/rzso0ac9x.css';
import '../../css/f/fj-sjk2rc.css';
import '../../css/i/ixk_98bub.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qqm0zqpjw"/><path class="rzso0ac9x"/><path class="fj-sjk2rc"/><path class="ixk_98bub"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:pen-tool-duotone" {...props}></Icon>
