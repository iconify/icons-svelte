<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-5w_6mjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":768};
const content = `<path class="z-5w_6mjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:alienship" {...props}></Icon>
