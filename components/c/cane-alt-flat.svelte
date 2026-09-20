<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk9y_wb6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="nk9y_wb6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:cane-alt-flat" {...props}></Icon>
