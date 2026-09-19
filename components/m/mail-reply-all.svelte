<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik1_o3bii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="ik1_o3bii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:mail-reply-all" {...props}></Icon>
