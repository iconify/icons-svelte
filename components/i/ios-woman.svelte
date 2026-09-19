<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rhpin-0sd.css';
import '../../css/y/y9o-uoblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rhpin-0sd"/><path class="y9o-uoblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-woman" {...props}></Icon>
