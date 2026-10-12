<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nm73mnbmi.css';
import '../../css/k/kgeq-sksu.css';
import '../../css/l/lo5duc4ee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="nm73mnbmi"/><path class="kgeq-sksu"/><path class="lo5duc4ee"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:flashlight-duotone" {...props}></Icon>
