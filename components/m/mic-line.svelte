<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7578qc1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7578qc1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mic-line" {...props}></Icon>
