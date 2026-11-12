<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvxxdu3wa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vvxxdu3wa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:affine-light" {...props}></Icon>
