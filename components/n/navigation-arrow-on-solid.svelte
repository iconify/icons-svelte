<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/reybrkbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="reybrkbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:navigation-arrow-on-solid" {...props}></Icon>
