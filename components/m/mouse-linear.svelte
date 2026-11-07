<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/ldt9ag-dz.css';
import '../../css/t/tw2a8j1nb.css';
import '../../css/g/glahfmzew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ldt9ag-dz"/><path class="tw2a8j1nb"/><path class="glahfmzew"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mouse-linear" {...props}></Icon>
