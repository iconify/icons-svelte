<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pkw64wbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pkw64wbcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:microscope-observation-sciene-solid" {...props}></Icon>
