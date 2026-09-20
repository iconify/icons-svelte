<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xung1lbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="xung1lbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:asset-network" {...props}></Icon>
