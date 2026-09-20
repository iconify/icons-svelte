<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr10hmbyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="dr10hmbyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:restore" {...props}></Icon>
