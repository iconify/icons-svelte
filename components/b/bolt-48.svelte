<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmx1_t3-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vmx1_t3-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bolt-48" {...props}></Icon>
