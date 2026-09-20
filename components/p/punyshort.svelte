<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uezgmdmvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uezgmdmvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:punyshort" {...props}></Icon>
