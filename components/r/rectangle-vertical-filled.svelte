<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdz78pbas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gdz78pbas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:rectangle-vertical-filled" {...props}></Icon>
