<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in1acbcxl.css';
import '../../css/g/g127gxnyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="in1acbcxl"/><path class="g127gxnyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-bus-48" {...props}></Icon>
