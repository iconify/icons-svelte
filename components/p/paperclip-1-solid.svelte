<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnpeo2jrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dnpeo2jrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:paperclip-1-solid" {...props}></Icon>
