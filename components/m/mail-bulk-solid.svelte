<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2xitt6tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l2xitt6tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:mail-bulk-solid" {...props}></Icon>
