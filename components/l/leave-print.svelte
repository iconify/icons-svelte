<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/ngehmsigm.css';
import '../../css/k/k44e6hbrh.css';
import '../../css/x/x2xhq2bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><rect class="ngehmsigm"/><path clip-rule="evenodd" class="k44e6hbrh"/><path class="x2xhq2bdm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:leave-print" {...props}></Icon>
