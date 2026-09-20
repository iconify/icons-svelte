<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flhmd_byi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="flhmd_byi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bug-virus-document-solid" {...props}></Icon>
