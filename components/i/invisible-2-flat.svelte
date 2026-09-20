<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usyesbc6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="usyesbc6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:invisible-2-flat" {...props}></Icon>
