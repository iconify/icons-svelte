<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oow9_6qcp.css';
import '../../css/d/d5ag-fmqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oow9_6qcp"/><path class="d5ag-fmqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:coupling-20" {...props}></Icon>
