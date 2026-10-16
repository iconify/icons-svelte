<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3d17v-0n.css';
import '../../css/o/ok69a315p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o3d17v-0n"/><path class="ok69a315p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ethernet-port-48" {...props}></Icon>
