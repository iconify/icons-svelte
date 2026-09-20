<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/q/q3r7l856c.css';
import '../../css/f/frvb35qqr.css';
import '../../css/h/h0aue6b3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="q3r7l856c"/><path class="frvb35qqr"/><path class="h0aue6b3g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:high-speed-train-front-flat" {...props}></Icon>
