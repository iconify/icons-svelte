<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw7qwioap.css';
import '../../css/l/l3qc97r_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yw7qwioap"/><path class="l3qc97r_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:network-nodes-48-bold" {...props}></Icon>
