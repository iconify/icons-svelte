<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gvrd7oq7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gvrd7oq7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fubotv" {...props}></Icon>
