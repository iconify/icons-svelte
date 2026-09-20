<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pykmghbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="pykmghbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:paperclip-1" {...props}></Icon>
