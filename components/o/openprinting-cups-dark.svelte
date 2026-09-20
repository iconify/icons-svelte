<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk6wy_3eo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tk6wy_3eo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openprinting-cups-dark" {...props}></Icon>
