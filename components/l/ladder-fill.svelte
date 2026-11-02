<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tn7_0n8ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tn7_0n8ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ladder-fill" {...props}></Icon>
