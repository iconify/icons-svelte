<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmatmabuy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rmatmabuy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:atlasnode-light" {...props}></Icon>
