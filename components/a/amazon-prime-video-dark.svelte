<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nna1dobij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nna1dobij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:amazon-prime-video-dark" {...props}></Icon>
