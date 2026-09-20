<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bguw7rb0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="bguw7rb0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:brightness-4" {...props}></Icon>
