<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qe8f_eb4j.css';
import '../../css/v/vjtl3vm_z.css';
import '../../css/k/krkzo_l8s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qe8f_eb4j"/><path class="vjtl3vm_z"/><path class="krkzo_l8s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:current-source-48-bold" {...props}></Icon>
