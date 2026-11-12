<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr96rnsfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1900,"height":1900};
const content = `<path class="qr96rnsfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gong-icon" {...props}></Icon>
