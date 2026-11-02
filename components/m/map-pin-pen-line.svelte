<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyqm8vbpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pyqm8vbpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:map-pin-pen-line" {...props}></Icon>
