<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlam0wbif.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dlam0wbif"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pinepods-light" {...props}></Icon>
