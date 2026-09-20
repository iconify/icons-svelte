<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zndlmvb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="zndlmvb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-arrows-button-to-left-arrow-line-to-left" {...props}></Icon>
