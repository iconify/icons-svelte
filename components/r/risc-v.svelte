<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4kcxyb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g4kcxyb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:risc-v" {...props}></Icon>
