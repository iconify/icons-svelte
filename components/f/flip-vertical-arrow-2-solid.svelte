<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyf8izpjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="iyf8izpjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:flip-vertical-arrow-2-solid" {...props}></Icon>
