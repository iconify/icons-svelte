<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp2j194ph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tp2j194ph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cloudinary-light" {...props}></Icon>
