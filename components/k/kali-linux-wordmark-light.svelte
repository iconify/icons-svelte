<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irtau8cwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="irtau8cwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kali-linux-wordmark-light" {...props}></Icon>
