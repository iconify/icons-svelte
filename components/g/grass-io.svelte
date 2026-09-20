<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y6m0izbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y6m0izbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:grass-io" {...props}></Icon>
