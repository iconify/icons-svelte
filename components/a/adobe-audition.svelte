<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv-k2s26h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tv-k2s26h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:adobe-audition" {...props}></Icon>
