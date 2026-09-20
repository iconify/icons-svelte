<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox-65bbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ox-65bbyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-diagonal-arrows-arrow-server-data-diagonal-internet-transfer-network" {...props}></Icon>
