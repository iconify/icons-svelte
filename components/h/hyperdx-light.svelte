<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5wad8b1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a5wad8b1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hyperdx-light" {...props}></Icon>
