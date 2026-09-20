<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8hce2bea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="l8hce2bea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:face-scan-1" {...props}></Icon>
