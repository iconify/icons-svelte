<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw1v71bwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dw1v71bwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nocodb-dark" {...props}></Icon>
