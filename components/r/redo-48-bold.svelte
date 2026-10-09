<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhdbk79fo.css';
import '../../css/q/qcnda-9od.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mhdbk79fo"/><path class="qcnda-9od"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:redo-48-bold" {...props}></Icon>
