<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmgot2wmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="cmgot2wmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:new-folder-solid" {...props}></Icon>
