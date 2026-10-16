<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qclimqb5u.css';
import '../../css/a/amrwb6zhd.css';
import '../../css/q/qy-1mwbkm.css';
import '../../css/x/xk-igwbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qclimqb5u"/><path class="amrwb6zhd"/><path class="qy-1mwbkm"/><path class="xk-igwbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:org-chart-20-bold" {...props}></Icon>
