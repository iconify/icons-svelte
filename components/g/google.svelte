<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llw355j1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="llw355j1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:google" {...props}></Icon>
