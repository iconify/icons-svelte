<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oicrqse3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="oicrqse3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:gift-2-solid" {...props}></Icon>
