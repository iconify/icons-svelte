<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd5ctr80z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="xd5ctr80z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:data-type-double" {...props}></Icon>
