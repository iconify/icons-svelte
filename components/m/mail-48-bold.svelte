<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/defz0cbcm.css';
import '../../css/k/khp0jolrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="defz0cbcm"/><path class="khp0jolrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mail-48-bold" {...props}></Icon>
