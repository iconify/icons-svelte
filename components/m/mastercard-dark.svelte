<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/engx1ybxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="engx1ybxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mastercard-dark" {...props}></Icon>
