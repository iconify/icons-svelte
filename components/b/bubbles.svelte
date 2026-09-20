<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/e/em57_pb1b.css';
import '../../css/q/q9cy_jv2z.css';
import '../../css/b/b0rut8bma.css';
import '../../css/p/p3twxs94c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="em57_pb1b"/><circle class="q9cy_jv2z"/><circle class="b0rut8bma"/><circle class="p3twxs94c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:bubbles" {...props}></Icon>
