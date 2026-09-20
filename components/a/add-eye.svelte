<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qkxnt0j7u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qkxnt0j7u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:add-eye" {...props}></Icon>
