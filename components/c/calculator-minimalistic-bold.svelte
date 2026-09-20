<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-vtm-dnt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g-vtm-dnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:calculator-minimalistic-bold" {...props}></Icon>
