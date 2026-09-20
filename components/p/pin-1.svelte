<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkslc6b1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="nkslc6b1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:pin-1" {...props}></Icon>
