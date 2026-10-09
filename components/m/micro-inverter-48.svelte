<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsgp-8odn.css';
import '../../css/u/unq7cxbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xsgp-8odn"/><path class="unq7cxbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:micro-inverter-48" {...props}></Icon>
