<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wabtt1w3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":488};
const content = `<path class="wabtt1w3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:apple" {...props}></Icon>
