<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca_z99bhx.css';
import '../../css/l/lg-kv2b6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ca_z99bhx"/><path class="lg-kv2b6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ppa-48" {...props}></Icon>
