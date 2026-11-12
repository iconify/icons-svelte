<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0g7ckb0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z0g7ckb0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:papermc-paper-light" {...props}></Icon>
