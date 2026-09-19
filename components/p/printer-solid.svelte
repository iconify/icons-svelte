<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/in1ns9bcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="in1ns9bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:printer-solid" {...props}></Icon>
