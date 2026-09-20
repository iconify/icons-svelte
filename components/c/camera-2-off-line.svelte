<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oykyflbit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oykyflbit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camera-2-off-line" {...props}></Icon>
