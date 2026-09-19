<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-e8jibpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":500,"height":512};
const content = `<path class="n-e8jibpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:bazaar" {...props}></Icon>
