<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1muudilt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c1muudilt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:realtor-com-light" {...props}></Icon>
