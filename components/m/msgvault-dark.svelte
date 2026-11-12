<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygu0xdb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ygu0xdb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:msgvault-dark" {...props}></Icon>
