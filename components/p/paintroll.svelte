<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zn5ux_btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="zn5ux_btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:paintroll" {...props}></Icon>
