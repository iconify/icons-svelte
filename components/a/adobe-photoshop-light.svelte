<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3ppw6pls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a3ppw6pls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:adobe-photoshop-light" {...props}></Icon>
