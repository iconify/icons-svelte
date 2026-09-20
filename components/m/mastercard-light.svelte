<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epykl_-yk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="epykl_-yk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mastercard-light" {...props}></Icon>
