<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhil_xbve.css';
import '../../css/h/hedtevnmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qhil_xbve"/><path class="hedtevnmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gps-20" {...props}></Icon>
