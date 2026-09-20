<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rx0_3vbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rx0_3vbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:download-circle-solid" {...props}></Icon>
