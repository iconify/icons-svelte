<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gyg2thb8e.css';
import '../../css/x/xmvfudb6x.css';
import '../../css/n/nep_y2bfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gyg2thb8e"/><path class="xmvfudb6x"/><path class="nep_y2bfc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:axe-duotone" {...props}></Icon>
