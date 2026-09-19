<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwv613bdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":448};
const content = `<path class="xwv613bdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:download-from-cloud" {...props}></Icon>
