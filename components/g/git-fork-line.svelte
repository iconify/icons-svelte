<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/v/vwtlgbhlv.css';
import '../../css/x/x-oeo5lde.css';
import '../../css/x/x1fksccrt.css';
import '../../css/d/dfqro5y3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><circle class="vwtlgbhlv"/><circle class="x-oeo5lde"/><circle class="x1fksccrt"/><path class="dfqro5y3h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:git-fork-line" {...props}></Icon>
