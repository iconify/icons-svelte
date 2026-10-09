<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q4ebx7sgh.css';
import '../../css/e/ebm8rubrc.css';
import '../../css/v/vskvwtb5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q4ebx7sgh"/><path class="ebm8rubrc"/><path class="vskvwtb5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:chart-pie-half-48-bold" {...props}></Icon>
