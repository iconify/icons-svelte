<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/ap6ym8bpq.css';
import '../../css/g/gj26gdbil.css';
import '../../css/p/pnn193b0s.css';
import '../../css/m/m15_1sz-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ap6ym8bpq"/><path clip-rule="evenodd" class="gj26gdbil"/><path class="pnn193b0s"/><path class="m15_1sz-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:can" {...props}></Icon>
