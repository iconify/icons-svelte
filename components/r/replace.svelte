<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfw6_rajk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="hfw6_rajk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:replace" {...props}></Icon>
