<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/goz9-9kzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="goz9-9kzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pinkary-dark" {...props}></Icon>
