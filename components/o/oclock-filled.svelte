<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbtugyycx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vbtugyycx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:oclock-filled" {...props}></Icon>
