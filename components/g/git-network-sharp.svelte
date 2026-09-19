<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-f9gnybm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w-f9gnybm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:git-network-sharp" {...props}></Icon>
