<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc3ilob8v.css';
import '../../css/o/ocwmt_j3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oc3ilob8v"/><path class="ocwmt_j3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:box-cutter-48" {...props}></Icon>
