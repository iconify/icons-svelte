<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/ms8h6zb9e.css';
import '../../css/q/qhfur2bdl.css';
import '../../css/b/bw3ufyb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ms8h6zb9e"/><path class="qhfur2bdl"/><path class="bw3ufyb3p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:chess-queen-duotone" {...props}></Icon>
