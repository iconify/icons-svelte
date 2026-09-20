<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1fvv2b8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="e1fvv2b8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:hospital-sign-solid" {...props}></Icon>
