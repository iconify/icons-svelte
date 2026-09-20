<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyarh0b7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kyarh0b7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:liwan-light" {...props}></Icon>
