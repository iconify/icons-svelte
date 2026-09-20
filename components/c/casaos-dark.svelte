<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7yq9sboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n7yq9sboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:casaos-dark" {...props}></Icon>
