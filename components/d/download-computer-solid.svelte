<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/soznv6kqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="soznv6kqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:download-computer-solid" {...props}></Icon>
