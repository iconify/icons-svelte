<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y02z66pwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="y02z66pwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:layout-window-8-solid" {...props}></Icon>
