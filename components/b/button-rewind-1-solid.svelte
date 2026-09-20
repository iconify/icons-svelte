<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhomdvb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jhomdvb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:button-rewind-1-solid" {...props}></Icon>
