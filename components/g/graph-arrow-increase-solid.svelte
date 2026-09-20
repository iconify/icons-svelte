<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjp1e-b0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="sjp1e-b0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:graph-arrow-increase-solid" {...props}></Icon>
