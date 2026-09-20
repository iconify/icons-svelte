<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi857sb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi857sb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:arrow-left-square-filled" {...props}></Icon>
