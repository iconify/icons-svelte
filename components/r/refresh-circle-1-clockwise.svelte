<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smi-2nbap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="smi-2nbap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:refresh-circle-1-clockwise" {...props}></Icon>
