<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9j72lbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="w9j72lbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:facebook-1" {...props}></Icon>
