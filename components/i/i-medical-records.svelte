<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti2jc9bbd.css';
import '../../css/p/p1sjyybhn.css';
import '../../css/o/onse16b0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="ti2jc9bbd"/><path class="p1sjyybhn"/><path class="onse16b0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-medical-records" {...props}></Icon>
