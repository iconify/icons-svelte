<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p_pe0sbpw.css';
import '../../css/n/nby40cd0q.css';
import '../../css/l/l7ocqgb5a.css';
import '../../css/n/nwe4nxbih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p_pe0sbpw"/><path class="nby40cd0q"/><path class="l7ocqgb5a"/><path class="nwe4nxbih"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:package-question-mark-duotone" {...props}></Icon>
