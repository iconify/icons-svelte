<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq6x_qc-w.css';
import '../../css/d/d2omkm1_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dq6x_qc-w"/><path class="d2omkm1_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:piggy-bank-48-bold" {...props}></Icon>
