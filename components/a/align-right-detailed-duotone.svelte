<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/ijpbx-baj.css';
import '../../css/s/sbw23ebxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ijpbx-baj"/><path class="sbw23ebxk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-right-detailed-duotone" {...props}></Icon>
