<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw4js04xx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="yw4js04xx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:powerplugus" {...props}></Icon>
