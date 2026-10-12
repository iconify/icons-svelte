<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cdet1bgca.css';
import '../../css/r/rlpnqsbdy.css';
import '../../css/g/gxe3u81da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cdet1bgca"/><path class="rlpnqsbdy"/><path class="gxe3u81da"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mountain-snow-duotone" {...props}></Icon>
