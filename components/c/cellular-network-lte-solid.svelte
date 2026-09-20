<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqsm_1b-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="aqsm_1b-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:cellular-network-lte-solid" {...props}></Icon>
