<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rrk1nfbye.css';
import '../../css/a/as_zecc1v.css';
import '../../css/c/cy496ybdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rrk1nfbye"/><path class="as_zecc1v"/><path class="cy496ybdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:currency-duotone" {...props}></Icon>
